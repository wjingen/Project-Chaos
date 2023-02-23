# Project Chaos

### Screenshots

Threat Page
![image](https://user-images.githubusercontent.com/74229021/220969448-29263d17-8f87-489d-847a-a1cd120e4924.png)
Impact Page
![image](https://user-images.githubusercontent.com/74229021/220969498-c4a14bdb-a7a3-46e0-a5fd-f74b6dc14369.png)
Response Page
![image](https://user-images.githubusercontent.com/74229021/220969542-a3d42fb5-4739-4180-b82c-ac3613ce97eb.png)



### Project Video

### A Data-Driven Dashboard to the Russian-Ukraine War

Project Chaos delves into the reactions, impacts and repercussions of the ongoing Russian-Ukraine war.

It is cleanly divided into three portions, **Threat**, **Impact** and **Response**.

The various stages of the data analysis cycle - from data collection, to data preprocessing and data visualisation was employed in the construction of this project.

### ✈️ Deployment

The project is deployed on Heroku and available [here](https://russia-ukraine-dashboard.herokuapp.com/main_dashboard).


### 🤔 Motivation

* View the impact behind a real-world and ongoing conflict - Using Data for good
* Practice web-scraping with BeautifulSoup
* Perform data cleaning and Exploratory Data Analysis on publicly-available datasets
* Explore the myraid of visualisation tools available for Python, such as Dash, Panel and Flourish

### 🏗 Architecture and Project Files

 The relevant files are split into two folders: 
```
csv_files/
jupyter-notebooks/ 
```
Within the jupyter-notebooks folder:
```
impact_1.ipynb
impact_2.ipynb
main_dashboard.ipynb
response_1.ipynb
response_2.ipynb
threat_1.ipynb
threat_2.ipynb
threat_3.ipynb
```

`main_dashboard.ipynb` is responsible for rendering all the outputs.

# 📚 Technologies/Libraries used

* Data Collection - BeautifulSoup
* Data Preprocessing - Pandas
* Data Analysis - Pandas & vaderSentiment (NLP)
* Data Visualisation - Plotly, Seaborn, Panel & Flourish
* Version Control - GitHub
* Deployment - Heroku


# 🚀  Takeaways

Data collection and cleaning takes up most of time in a project. The sources came from multiple organisations and sources, and the merging and preprocessing of data was a tedious but necessary process. Proper isolation of the development environment was done using the `virtualenv` module, so as to ensure replicability.


