# Seattle Airbnb CRISP-DM Project

**Author:** Sajid Al Sanai

**License:** MIT

## 1. Motivation

I utilise data regarding listings of properties by Airbnb hosts in the city of Seattle (WA) between 2016-2017 for data and regression analysis using the CRISP-DM process. I identify several questions of business interest which I attempt to answer through analysis of the available data.

These questions include:
1. What are the highest rated areas to to reserve accomodations in Seattle?
2. What are the highest revenue generating neighbourhoods in Seattle?
3. Which scores are most important to overall ratings? (Linear Regression)
4. Do hosts with higher ratings overall earn higher revenue? (Linear Regression)
5. What are the most widely provided amenities listed by hosts in Seattle?
6. Which amenities, housing characteristics, and factors contribute positively to revenue? (Linear Regression)
7. Which amenities, housing characteristics, and factors contribute positively to ratings? (Linear Regression)

## 2. Installation

This project consists of a Python notebook created with Jupyter Lab and standard Python packages for data analysis and machine learning.

You may open Python notebooks using Jupyter Lab, Visual Studio Code, or PyCharm, which are all IDEs in which notebooks can be created and modified.

Python packages I have used for this project include:
1. NumPy
2. Pandas
3. Matplotlib
4. Seaborn
5. Scikit-Learn

You may install these using the following *bash* code in a UNIX-based environment:
```bash
python3 -m pip install --upgrade pip
python3 -m pip install venv
venv env
source env/bin/activate
python3 -m pip install numpy pandas matplotlib seaborn scikit-learn
deactivate
```

## 3. Files
- README.md
- LICENSE.md
- seattle-airbnb-crispdm.ipynb
- seattle-airbnb-crispdm.html
- calendar.csv
- listings.csv
- reviews.csv

To download this repository to your local system, you may navigate to the directory where you wish to download the files and use the following UNIX-based *bash* code:
```bash
git clone https://github.com/sajidsarker/seattle-airbnb-crispdm.git
```

To run the Python notebook, please download and run *seattle-airbnb-crispdm.ipynb*, while making sure *listings.csv* and *reviews.csv* are downloaded to the same directory. 

## 4. Data

Datasets utilised are provided by Airbnb solely for the city of Seattle (WA), divided into (3) CSV files which are included in the same repository directory as my Python notebook. Of these (3) datasets, I utilise only (2) which are most relevant and useful for my analysis:
1. Listings
2. Reviews
3. Calendar (unused)

I have, however, included all (3) datasets above as part of this repository for completeness.

## 5. Analysis & Evaluation

Preliminary analysis of my results are available in the accompanying notebook within this repository. However, a more verbose narrative, analysis, and evaluation are available in my blog post discussing the final results I have obtained.

[Access my blog post for analysis.](https://sajidsarker.github.io/2022/08/30/seattle-airbnb-crisp-dm-project.html)
