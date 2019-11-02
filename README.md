# Disaster Response Pipeline Project

## Table of Contents
1. [Description](#description)
2. [Getting Started](#getting_started)
	1. [Folder and File Structure](#folder_and_file_structure)
	2. [Dependencies](#dependencies)
	3. [Installing](#installing)

<a name="descripton"></a>
## Description

The initial dataset contains pre-labelled tweet and messages from real-life disaster. 
The goal is to build a Natural Language Processing tool that categorizes messages.

The project is divided in the following Sections:

1. Data Processing, ETL Pipeline to extract data from source, clean data and save them in a proper databse structure
2. Machine Learning Pipeline to train a model able to classify text message in categories
3. Web App to show model results in real time. 

<a name="getting_started"></a>
## Getting Started

<a name="folder_and_file_structure"></a>
### Folder and File Structure

* app <br />
	* template <br />
		* master.html  # main page of web app <br />
		* go.html  # classification result page of web app <br />
	* run.py  # Flask file that runs app <br />
* data <br />
	* disaster_categories.csv  # data to process <br />
	* disaster_messages.csv  # data to process <br />
	* process_data.py <br />
	* InsertDatabaseName.db   # database to save clean data to <br />
* models <br />
	* train_classifier.py <br />
	* classifier.pkl  # saved model <br />
* README.md <br />

<a name="dependencies"></a>
### Dependencies
* Python 3.5+ (I used Python 3.7.4)
* Machine Learning Libraries: NumPy, SciPy, Pandas, Sciki-Learn
* Natural Language Process Libraries: NLTK
* SQLlite Database Libraqries: SQLalchemy
* Web App and Data Visualization: Flask, Plotly

<a name="installing"></a>
### Installing
Clone this GIT repository:
```
git clone https://github.com/kchebs/disaster_response_pipeline.git
```
