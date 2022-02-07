# financial_planning_tools
Leveraging Monte Carlo method to assess future value of a portfolio with different risk compositions to compare probable balances at 10 and 30 years from now
[![LinkedIn][linkedin-shield]][linkedin-url]
<!-- [![License][license-shield]][license-url] -->

<!-- PROJECT LOGO -->
<br />
<p align="center">
    <img src="https://github.com/evianap/financial_planning_tools/blob/main/Images/5-4-challenge-image.png" alt="Financial Planning">
  </a>

  <h3 align="center">financial_planning_tools_</h3>

  <p align="center">
    Evaluating Future Fund Balance    <br />
    <a href="https://github.com/evianap/financial_planning_tools"><strong>Go to documents »</strong></a>
    <br />
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

<p>This project is designed to assess future balance of a portfolio with different risk compositions to compare probable balances at 10 and 30 years from now<p/>


<p align="center"><img src="https://github.com/evianap/financial_planning_tools/blob/main/Images/MCSimulation1.png" alt="MC1"><p/>

<p>Simulation results are analyzed<p/>

<p align="center"><img src="https://github.com/evianap/financial_planning_tools/blob/main/Images/MCSimulation1Analysis.png" alt="MC1A"><p/>

<p>Simulation is ran under different assumptions (time and portfolio composition) and analyzed<p/>

<p align="center"><img src="https://github.com/evianap/financial_planning_tools/blob/main/Images/MCSimulation2.png" alt="MC2"><p/>
<p align="center"><img src="https://github.com/evianap/financial_planning_tools/blob/main/Images/MCSimulation2Analysis.png" alt="MC2A"><p/>

### Built With

<!-- This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples. -->

* [Python](https://www.python.org/)
* [Jupyter Lab](https://jupyter.org/install)

### Prerequisites

<!-- This is an example of how to list things you need to use the software and how to install them. -->
A variety of libraries were used and are needed for this program. They need to be installed (except for MCForecast Tools which is a dependency):

``` 
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation

%matplotlib inline
```



<!-- CONTACT -->
## Contact

Enrique Viana - [@evianap][linkedin-url] - j.enrique.viana@gmail.com

Project Link: [https://github.com/evianap/whale_analysis](https://github.com/evianap/whale_analysis)

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Kevin Lee](https://github.com/kevinclee26/)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

<!-- [license-shield]: 
[license-url]:  -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/enriqueviana/# financial_planning_tools
Financial planner for emergencies and for retirement
