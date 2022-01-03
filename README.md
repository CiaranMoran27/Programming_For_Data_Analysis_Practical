
***
<h2>GMIT: Programming for Data Analysis</h2>
<h2>Modelling Real World Data: Blood Pressure</h2>

***

<br>

### Description
***
This repository contains all the files relevant to my 2021 Programming fo Data Analysis Project. The project<br>
explored blood pressure and what variables potentially effected it (i.e: BMI, body fat percentage, age and sex).<br>
The distribution of all the variables and their correlations were also explored and modelled in the form of a<br>
dataset and pairplot. Note: the distribution statistics and correlation data was modelled from a previous study<br>
(see Creditation Section of README). Lastly, a Multiple Linear Regression Model was ran on a subset of the<br>
dataset and results compared against previous study.

<br>

### Motivations
***
The aim of this project was to select a real world phenomenon, investigate the types of variables involved,<br>
their likely distributions and their relationships with eachother. Armed with this information the main task was<br>
to simulate a dataset closely matching the variable properties. The ability to simulate real world data accurately<br>
has many benifits in prediciting probabilities and in the world of machine learning.

<br>


### Contents of repository:<br />
***
1. **modelling_real_world_scenario.ipynb**: <br />  
    - This Jupyter notebook contains the research, dataset simulation code and plots relating to the project. <br>
    - Quicklinks below: *nbviewer* for static view:<br />
        
        <br />
        
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/CiaranMoran27/Programming_For_Data_Analysis_Project/blob/fc228be33daabdc70f4d35560c75a5ff286627ea/modelling_real_world_scenario.ipynb) 
     
   <br />
     

2. **requirements.txt file**:   
This file contains the packages necessary to run the Jupyter notebook.
<br /> 



### Running notebooks locally
***
1. Download [Anaconda](https://docs.anaconda.com/anaconda/install/index.html), this contains the python 
interpreter and libraries needed to run this notebook.
2. Download [cmder](https://cmder.net/) if working on a Windows Operating System, alternatively use the basic *command <br>line interface*
if working on a Linux or Mac operating system.
3. Clone [repository](https://github.com/CiaranMoran27/Programming_For_Data_Analysis_Project) as laid out [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).
4. Run '*jupyter lab*' command on:
    - *Cmder* if working on a Windows operation system.
    - *Command line interface* if working on a Linux or Mac operating system.
    
**Note:**<br>
Although Anacondas contains the required packages to run the notebook, if one has [python](https://www.python.org/downloads/) already<br>
downloaded and would prefer to individually download the required libraries, its possible to do this by<br>
leveraging the requirements.txt file via the following command: (adjust path accordingly): <br />

``` Python
pip install -r /path/requirements.txt
```

<br>


### Using The Jupyter Notebook:
***
The Jupyter notebook has 3 important usage points for simulating the data. These cells are located at the<br>
following sections (Simulation Cells) of the notebook and can be ran to simulate different results:<br>
- 7.2 Simulating the dataset as a pairplot.
    - Swap the hue_value variable at top of cell between 'BP category' and 'gender' to view different<br>
    relationships.
- 8.2 Simulating Multiple Linear Regression Model Comparison
- 10.2 Simulating dataframe printout

<br>

### Project Outcomes:
***
- **Variable allignment:**
    - The project sucessfuly modelled the given distirbutions and correlations and showed the accuracy pre-and<br>
    post model.<br>

- **Overall:**
    - This project showed how accurate the numpy multivariate_normal module is at modelling normally distributed<br>
variables when given a mean, standard deviation and co-variance matrix. It also successfully illustrated how<br>
one can replicate Linear Regression Models using sklearn. 


<br>

### Creditation
***
This project relied heavily on the study carried out by Boledovičová, M et al. (2013), using distribution statistics and<br>
correlation co-efficients from this study to help model this projects dataset. The study did not release the actualy data<br>
but did declare the distribution statistics, Pearsons correlation co-efficients and the equation of the line formula for<br> 
Multiple Linear Regression Models.<br><br>
**Reference:**<br>
Boledovičová, M et al. (2013), Blood pressure relation to body composition and age: Analysis of a nurse-led<br>
investigationand consultation program, Available at: Ref Link 2, (Accessed 13 December 2021).

