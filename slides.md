
## Tomasz Janus
<!-- .slide: style="text-align: left;"> -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
    .img.rounded {
        border-radius: 5%;
        box-shadow: 5px 5px 15px rgba(255, 255, 255, 0.2);
    }
</style>
<img src="images/tomasz-cropped.jpg" class="img custom rounded" style="float: right; align-items: center;" width="300"/>

### Research Associate
<p><img src="images/tyndall_logo-cropped-small.jpg" 
style="display:block; border-radius: 10px; box-shadow: 2px 2px 10px rgba(255, 255, 255, 0.4);" 
width="300"/></p>

<i class="fa fa-envelope"></i><a href="mailto:tomasz.janus@manchester.ac.uk"> tomasz.janus@manchester.ac.uk</a><br>

<i class="devicon-linkedin-plain"></i> <a href="https://www.linkedin.com/in/tomasz-janus-6443b7198"> Linked<b>in</b> Profile</a> <br>

<i class="fa fa-github"></i> <a href="https://github.com/tomjanus"> github.com/tomjanus</a>

---

<!-- .slide: style="text-align: center;"> -->
<h2> <i style="color: #FF7A59">Open & Reproducible</i> in a Large Multinational Project? </h2>
<h3 class="r-fit-text"> Low-Emission Hydroelectric Dam Expansion Planning in Myanmar </h3>
<img src="images/upper_paunglaung.jpg" 
    style="float: left; border-radius: 5%; box-shadow: 0px 0px 10px rgba(255, 255, 255, 1)" height="270">
<img src="images/myanmar.webp" 
    style="float: right; border-radius: 5%; box-shadow: 0px 0px 10px rgba(255, 255, 255, 1)" height="270">

---

## Presentation Plan

<style>
  .fragment.blur {
    filter: blur(5px);
  }
  .fragment.blur.visible {
    filter: none;
  }
</style>
<section>
  <p>Project <b style="color: #c48560">Introduction</b></p>
  <p class="fragment custom blur">Which <b style="color: #82401a">Open Research</b> Practices Have We Adopted and Why?</p>
  <p class="fragment custom blur"><b style="color:  #a6826d">Challenges, Benefits, Opportunitiess</b></p>
  <p class="fragment custom blur"><b style="color: #694d3d">Lessons</b> Learned</p>
  <p class="fragment custom blur">What's in it for Us in the <b style="color: #824f35">Future</b>?</p>
</section>

---

# The Team
<!-- .slide: style="text-align: center; font-size: 30px"> -->
<style>
    img.faces {
    width: 110px;
    height: 110px;
    border-radius: 10%;
    }
</style>
<table>
  <tr>
    <td align="center"><img class="img custom faces" src="images/tomasz-cropped.jpg" alt=""/><br /><sub><b>Tomasz Janus</b> (UoM-Tyndall)</sub><br /></td>
    <td align="center"><img class="img custom faces" src="images/boy.png" alt=""/><br /><sub><b>Chris Barry</b> (UKCEH)</sub><br /></td>
    <td align="center"><img class="img custom faces" src="images/kamilla-cropped.jpg" alt=""/><br /><sub><b>Kamilla Kopec-Harding</b> (Research IT)</sub><br /></td>
    <td align="center"><img class="img custom faces" src="images/shelly-cropped.jpg" alt=""/><br /><sub><b>Shelly Win </b> (IWMI Myanmar)</sub><br /></td>
    <td align="center"><img class="img custom faces" src="images/jojo-cropped.jpg" alt=""/><br /><sub><b>Aung Kyaw Kyaw </b> (Yangon University)</sub><br /></td>
    <td align="center"><img class="img custom faces" src="images/jaise-cropped.jpg" alt=""/><br /><sub><b>Jaise Kuriakose</b> (UoM-Tyndall)</sub><br /></td>
  </tr>
</table>

---

## Funding

This research was funded by the [University of Manchester](https://www.manchester.ac.uk/) and the [FutureDams](https://www.futuredams.org/) project.

<table style="border: 0px hidden white;margin-left:auto;margin-right:auto;">
  <tr>
<td align="center"><a href="https://www.manchester.ac.uk/"><img src="images/TAB_col_background.png" 
style="margin: 0px 0px 0px 0px; box-shadow: 10px 10px 25px rgba(255, 255, 255, 0.25)"
height="90px;" alt=""/></td>
<td align="center"><a href="https://www.futuredams.org/"><img src="images/future-dams-logo.png" 
style="margin: 0px 0px 0px 120px; box-shadow: 10px 10px 25px rgba(255, 255, 255, 0.4)"
height="90px;" alt=""/></td>
  </tr>
</table>

We also acknowledge the help received from [UKCEH](https://www.ceh.ac.uk/) and the support from [Research IT](https://research-it.manchester.ac.uk/)
<table style="border: 0px hidden white;margin-left:auto;margin-right:auto;">
  <tr>
<td align="center"><a href="https://www.ceh.ac.uk/"><img src="images/UKCEH-Logo_Long_WhiteOut_RGB-Transparent.png" 
style="margin: 0px 0px 0px 0px; box-shadow: 10px 10px 25px rgba(255, 255, 255, 0.25)"
height="90px;" alt=""/></td>
<td align="center"><a href="https://research-it.manchester.ac.uk/"><img src="images/research-it-logo.png" 
style="margin: 0px 0px 0px 60px; box-shadow: 10px 10px 25px rgba(255, 255, 255, 0.25)"
height="90px;" alt=""/></td>
  </tr>
</table>

---

## Part 1. Free Open Source Software
<!-- .slide: style="text-align: center; font-size: 30px"> -->
<style>
.columns {
    display: flex;
    justify-content: space-between; /* Adjust as needed */
}

.column-left,
.column-right {
    width: 48%; /* Adjust as needed */
}

/* Adjust for responsive design */
@media screen and (max-width: 768px) {
    .columns {
        flex-direction: column;
    }
    .column-left,
    .column-right {
        width: 100%;
    }
}

img.software_logos {
    width: 450px;
    border-radius: 10px;
    opacity: 0.9;
    }

</style>

<section>
    <div class="columns">
        <div class="column-left">
            <!-- Content for the left column goes here -->
            <img style="padding-top: 50px; opacity:0.85" src="images/graphical_abstract_openresearch_left.drawio.png" height="550vh"/>
        </div>
        <div class="column-right" style="padding-top: 30px">
            <!-- Content for the right column goes here -->
            <p class="fragment fade-down" data-fragment-index="1"><img class="img software_logos" src="images/geocaret_logo.png" alt=""/></p>
            <p class="fragment fade-down" data-fragment-index="1">Geospatial Analysis of Reservoirs and Catchments with Google Earth Engine and Python</p>
            <p class="fragment fade-down" data-fragment-index="2"><img class="img software_logos" src="images/logo-banner-bw.png" alt=""/></p>
            <p class="fragment fade-down" data-fragment-index="2"><a href="https://github.com/tomjanus/reemission">Estimation and Visualisation of GHG Emissions from Reservoirs</a></p>
            <p class="fragment fade-down" data-fragment-index="2" style="font-size: 22px; color: #268758">We developed both packages out of necessity</p>
        </div>
    </div>
</section>

---

## Part 2. Interpretation of Results
<!-- .slide: style="text-align: center; font-size: 30px"> -->
<style>
.columns {
    display: flex;
    justify-content: space-between; /* Adjust as needed */
}

.column-left,
.column-right {
    width: 48%; /* Adjust as needed */
}

/* Adjust for responsive design */
@media screen and (max-width: 768px) {
    .columns {
        flex-direction: column;
    }
    .column-left,
    .column-right {
        width: 100%;
    }
}

img.software_logos {
    width: 450px;
    border-radius: 10px;
    opacity: 0.9;
    }

</style>

<section>
    <div class="columns">
        <div class="column-left">
            <!-- Content for the left column goes here -->
            <img style="padding-top: 50px; opacity:0.85" src="images/graphical_abstract_openresearch_middle.drawio.png" height="550vh"/>
        </div>
        <div class="column-right" style="padding-top: 50px">
            <!-- Content for the right column goes here -->
            <div style="text-align: left">
            <p><i class="fa fa-eye" style="color:#b3482b"></i> Interpretations Provide Another Layer of Transparency</p>
            <p><i class="fa fa-exclamation" style="color:#b3482b"></i> Important for Gaining Confidence in Model Predictions</p>
            <p><i class="fa fa-handshake-o" style="color:#268758"></i> Useful source of information in decision-making</p>
            </div> 
            <div>
            <img src="images/dalex_even.png" width=120px style="border-radius: 50%;"/>
            <p style="font-size: 20px">We used <a href="https://dalex.drwhy.ai/">DALEX</a> - A moDel Agnostic Language for Exploration and eXplanation implemented in <b>R</b> and <b>Python</b>.</p>
            </div>
        </div>
    </div>
</section>

---

## Part 3. Computation & Reproducibility
<!-- .slide: style="text-align: center; font-size: 30px"> -->
<style>
.columns {
    display: flex;
    justify-content: space-between; /* Adjust as needed */
}

.column-left,
.column-right {
    width: 48%; /* Adjust as needed */
}

/* Adjust for responsive design */
@media screen and (max-width: 768px) {
    .columns {
        flex-direction: column;
    }
    .column-left,
    .column-right {
        width: 100%;
    }
}

img.software_logos {
    width: 450px;
    border-radius: 10px;
    opacity: 0.9;
    }

</style>

<section>
    <div class="columns">
        <div class="column-left">
            <!-- Content for the left column goes here -->
            <img style="padding-top: 50px; opacity:0.85" src="images/graphical_abstract_openresearch_right.drawio.png" height="550vh"/>
        </div>
        <div class="column-right" style="padding-top: 50px">
            <!-- Content for the right column goes here -->
            <div style="text-align: left">
            <p><i class="fa fa-eye" style="color:#cf961b"></i> Model and Algorithm parsimony helps with reproducibility</p>
            <p><i class="fa fa-btc" style="color:#b3482b"></i></i> Computation Costs Are Important for Reproducibility</p>
            <p><i class="fa fa-legal" style="color:#349cc2"></i> Deterministic vs. Stochastic (e.g. Genetic Algorithms)?</p>
            </div> 
            <div>
            <img src="images/tree-structured-networks.png" width=260px style="border-radius: 10px"/>
            <p style="font-size: 20px">We used <a href="https://github.com/gomes-lab/Dam-Portfolio-Selection-Expansion-and-Compression-CPAIOR">a fully polynomial-time approximation scheme that approximates the Pareto frontier on tree-
structured networks of Bai et al.</a></p>
            </div>
        </div>
    </div>
</section>

---

### Challenges - Benefits - Opportunities

<img class="r-stretch" style="border-radius: 20px; box-shadow: 10px 10px 35px rgba(180, 180, 180, 0.35);" src="images/open-research-practices-scaled.png" />

---

<h2>Sharing Models with <i style="color: #FF7A59">Leaflet.js</i></h2>

<iframe class="r-stretch" 
style="border-radius: 20px; box-shadow: 15px 15px 35px rgba(180, 180, 180, 0.35);"
src="https://tomjanus.github.io/mya_emissions_map/" frameborder="0" allowfullscreen>
</iframe>
<style>
  .left {
    text-align: left;
  }
</style>
<p style="font-size: 25px">Source: <a href="https://tomjanus.github.io/mya_emissions_map/">  https://tomjanus.github.io/mya_emissions_map/</a></p>

---

<h2>Sharing results with <a href="https://plotly.com/examples/" style="color: #FF7A59">Plotly DASH</a></h2>

<iframe class="r-stretch" 
style="border-radius: 20px; box-shadow: 15px 15px 35px rgba(180, 180, 180, 0.35);"
src="https://drawit-moea-results.onrender.com/" frameborder="0" allowfullscreen>
</iframe>
<style>
  .left {
    text-align: left;
  }
</style>
<p style="font-size: 25px">Source: <a href="https://drawit-moea-results.onrender.com/">  https://drawit-moea-results.onrender.com/</a></p>

---

<!-- Place this in your header -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.14.0/devicon.min.css">

## Lowering entry barrier with <i class="devicon-docker-plain-wordmark"></i>

<pre><code data-line-numbers="1|3|5-8|10|12|14">FROM mcr.microsoft.com/mssql/server:2019-CU5-ubuntu-18.04

USER root

RUN mkdir /var/opt/sqlserver
RUN mkdir /var/opt/sqlserver/sqldata
RUN mkdir /var/opt/sqlserver/sqllog
RUN mkdir /var/opt/sqlserver/sqlbackups

RUN chown -R mssql /var/opt/sqlserver

USER mssql

CMD /opt/mssql/bin/sqlservr
</pre></code>

---