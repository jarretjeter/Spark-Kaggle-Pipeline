# _Spark Kaggle Pipeline_

#### By _**Jarret Jeter**_

#### _Here I create an ETL pipeline from the website Kaggle to Google BigQuery using mainly Apache Spark, but Pandas for the very end_

## Technologies Used

* _Python_
* _Spark_
* _Pandas_
* _Google BigQuery_

## Description

The dataset that's downloaded contains information on U.S. coffee stocks, starting from the year 2000 to 2022. I perform aggregations on columns and create new columns to gather more information. Also I use the matplotlib library to visualize the changes in the data over time.

## Setup/Installation Requirements

* _Make sure you have a text editor such as Visual Studio Code installed, a python3.7 virtual environment active, and also a linux bash terminal to use_
* _Clone this repository (https://github.com/jarretjeter/Spark-Kaggle-Pipeline.git) onto your local computer from github_
* _In VS Code or another text editor, open this project_
* _With your terminal, 'pip install -r requirements.txt' to get the necessary dependencies_
* _Run the get_data.sh command in your terminal to obtain the csv file from Kaggle_
* _Once obtained, you can go into the main.ipynb file and run the notebook cells one by one to move along the data pipeline process_
* _To run the last cell which loads to Google BigQuery, you will need an account on Google Cloud Platform and a project to load to, as well as credentials set up on your local environment_

## Known Bugs

* _No known bugs_

## License

_If you have any questions, please email me at jarretjeter@gmail.com_

[MIT](https://github.com/jarretjeter/Spark-Kaggle-Pipeline/blob/main/LICENSE.txt)

Copyright (c) _07/04/2022_ _Jarret Jeter_