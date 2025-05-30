# Cyber-attacks-analysis
Exploratory analysis and visualization project using Power BI on the global cyberattacks. Project includes basic EDA and charts.

# Questions the datasets aims to answer
1. How many countries are affected by these attack?
2. How those countries' industries are affected?
3. Is the rate of attacks on those countries improving or worsening over the year?
4. How are some countries' rates of attacks compared to other countries?
5. What are the common attack type (like SQLi, phishing, etc...) that are being used?
6. How are those attacks impacting the country (users, financial loss, etc...)

# Dataset
The dataset used consists of 3000 rows of data, over 10 columns as follow:
* Country: Country where the attack has happened
* Year: year when attack happened
* Attack Type: how the attacks was done (phishing, virus, ransomware, etc...)
* Target Industry: industry targetted such as education, IT, government, etc...
* Financial Loss (in Million $)
* Number of Affected Users
* Attack Source: hacker group, nation-state attacks, insider, or unknown source
* Security Vulnerability Type: what was vulnerable and helped the attacker to hack
* Defense Mechanism Used: what was used to defend against the attacker
* Incident Resolution Time (in Hours): in how many hours the incident was fixed

The dataset is downloaded from [Kaggle](https://www.kaggle.com/datasets/atharvasoundankar/global-cybersecurity-threats-2015-2024). Or, you can find the csv file under `data` folder in this repository.

# Tools
* Microsoft Power BI (for data visulizations)
* Python (pandas library) for data exploration and analysis
* Google colab (runtime)
* Kaggle

# Data Analysis
Kindly refer to the `data analysis` folder and download the existing Jupyter Notebook file and run it against the csv file under `data` folder. After running the notebook, all analysis  made on the data should be seen in the notebook

# Data visualizations
Kindly download the latest version of Microsoft Power BI. After installing it, download the dashboard existing in the `dashboard` folder in this repository. After downlading the software and the dashboard, kindly open the dashboard in the app and all the visuals should be seen there.

# License
For licensing check the [LICENSE](LICENSE.md)
  
