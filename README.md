# EJScreen Data Exploration

#### -- Project Status: [Completed]

## Project Intro/Objective
The Environmental Protection Agency created an Environmental Justice Screening and Mapping Tool called EJScreen that tracks both demographic and environmental factors that impact environmental health. Having socioeconomic information linked with environmental indexes allows researchers to draw connections between the two to determine how there is inequity in environmental health. The dataset we chose tracks these factors on a national level, including education level, traffic proximity, ozone, unemployment rate, and low-income. We can use the EJScreen data to find correlation between these variables to identify potential risks in environmental health for underprivileged demographics.

### Methods Used
* Inferential Statistics
* Data Visualization

### Technologies
* R 

## Project Description

### Burden of environmental degredation on vulnerable populations
Environmental justice seeks to address the disproportionate burden of environmental degradation and pollution on marginalized communities. 

Vulnerable populations suffer the most from ecological harm, perpetuating systemic inequalities and endangering public health.

Past research (1990-2016) has found that marginalized communities are disproportionately exposed and affected by pollution and hazardous exposures due to the built infrastructure.

The Environmental Protection Agency created an Environmental Justice Screening and Mapping Tool called EJScreen that tracks both demographic and environmental factors that impact environmental health. Having socioeconomic information linked with environmental indexes allows researchers to draw connections between the two to determine how there is inequity in environmental health. The dataset we chose tracks these factors on a national level, including education level, traffic proximity, ozone, unemployment rate, and low-income. We can use the EJScreen data to find correlation between these variables to identify potential risks in environmental health for underprivileged demographics.

Our motivation behind choosing this dataset is to see if socioeconomic factors such as education level or unemployment rate have a correlation with environmental factors that pose a risk to an individual’s physical and mental well-being. Additionally, we can draw comparisons across geographic borders by filtering by states. For example, less densely populated states might have lower levels of environmental health disparities as compared to those in more densely populated states. Furthermore, we can isolate states and look at data in a specific state if we see something of interest during our initial analysis.

## Needs of this project
- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting


#### Prerequisites
- R & RStudio installed on your machine
- `renv` package installed. You can install it by running this command in R: `install.packages("renv")`

## Getting Started
1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Manage project dependencies by running `renv::restore()`.
3. Download the data from [this Google Drive link](https://drive.google.com/file/d/1d_70M8TcARCHt6jaqivX84Wr3TUiWSac/view?usp=sharing)
4. Unzip/uncompress the data and move it to the EDA_EJScreenData directory
5. Data processing/transformation and analysis is conducted in the `EDA_final.Rmd`.

### Repo Structure 
EDA_EJScreenData

    ├── README.md
    
    ├── EDA_final.Rmd
    
    ├── EDA_final.html # html version of the Rmd file
    
    ├── renv.lock #this contains meta data of dependencies used for this project
    
    ├── data/ # download this using the GoogleDrive link above
    
        └── env-data.csv
    
    └── renv/ # used for the renv package
    
        ├── activate.R
        
        └── settings.json


## Featured Notebooks/Analysis/Deliverables
* [Notebook/Markdown/Slide Deck Title](link)
* [Notebook/Markdown/Slide DeckTitle](link)
* [Blog Post](link)


## Contributing Members
|[Ayesha Saeed](https://github.com/[ayeshasaeed97])| 
|[Nathan Yoo](https://github.com/[yoo-nathan])|

## Contact 
ayesha.saeed@emory.edu
nathan.yoo@emory.edu 
