# Open Research Conference 2024 - Wednesday, 24 April, 2024
## The University of Manchester Open Research Award 2024

This is a repository containing slides for a presentation delivered at the
[Open Research Conference](https://www.openresearch.manchester.ac.uk/news-events/events/or-conference-24/) held at the University of Manchester on 24 April 2024.

## Summary

### Title

*"Open and Reproducible in a Large Multinational Project? - Low-Emission Hydroelectric Dam Expansion Planning in Myanmar"*

### Key Take-aways

* Achieving transparency and reproducibility in research requires many open research practices coming at once - open software/scripts/methodologies, open data, accessibility, audit-ability, documentation, choosing right models, and so on. The list is long.
* It is not always possible to tick all the boxes but aiming for transparency and openness and making your work reproducible by others will increase the impact of our work and reach more people.
* A lot of processes that we apply in open research are adopted from IT - version control, automated testing, documentation, integration pipelines, data custody, etc. and are difficult to achieve without the help of specialists. More high-level tools are needed for the research community that abstract some of these low level tasks and thus, reduce complexity and work-load.
* We show-cased some of the open research concepts that we applied in the context of a large project in Myanmar on planning low carbon emission hydropower sector expansion strategies.

### Selected Open Research Practices Showcased in Our Project

1. We created two bespoke free open-source software packages in Python.
2. We add explanations to model predictions using explainable AI (xAI) techniques. This step increases transparency by explaining which inputs and by how much contributed to predictions and is invaluable for decision makers.
3. We use parsimonious fast and deterministic optimization algorithm that enables reproducibility and allows the readers to replicate results without needing to access expensive computing facilities. This is in contrast to e.g. large formulations with Genetic Algorithms that can be computationally intensive and do not guarantee reaching the (optimal) solution.
4. We sets up models (descriptions, configurations and inputs) in text format e.g. JSON that can be version controlled and integrated into deployment pipelines such as GitHub actions. This ensures that everyone on the team can work with the most current version of the model and prevents mistakes due to people working on different versions of the model. Changes to the models are automatically integrated into workflows and can be visualised online using on GitHub pages.
5. We allow models and software to be optionally deployed in Docker containers which ensures that each user has the same working environment. This prevents mismatches due to incompatible/outdated packages and thus facilitates reproducibility. 

## How to view

This presentation is available online at : [https://github.com/tomjanus/openresearch2024-presentation/](https://github.com/tomjanus/openresearch2024-presentation/tree/gh-pages)

You can also serve it locally e.g. on **localhost:8080**. In Python this would be done by typing
`
python -m http.server 8080
`
in the root directory where `index.html` is located
