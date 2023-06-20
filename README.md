# challenge-11-060123
---
# FinTech BootCamp challenge 11
---
# Forecasting Net Prophet
**Using Facebook Prophet
![image from the fintech challenge 11](/images/11-4-challenge-image.png)
The purpose of challenge 11 was to use Facebook Prophet to analyze if the ability to predict search traffic can translate into the ability to successfully trade the stock of the MercadoLibre commerce site.

## Technologies
This project leverages python 3.7 specifically and assumes that jupyter lab has been installed. In additon, you would need to have the following modules installed:

* pandas
* hvplot
* holoviews
* pystan
* prophet

## Resources
* Data provided by Columbia FinTech program.

## Contributions 

Historical data and challenge questions provided by Columbia FinTech progam.
Analysis, code, and conclusions completed by Sean Senhouse

## Installation Guide
To run this project you would need to use google colab. Use the link below to launch google colab and view linking instructions

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)

To run the file in Google Colab use the following link
[![forecasting_net_prophet]](https://colab.research.google.com/drive/15aFjji9XvDATQqPau7Vq7yiP5Si25ROI?usp=sharing)

## Usage

The code imports files from 3 CSV files as data source. The model output generates several charts to summarize the report. 

## Final Results
The following charts are output from the FB prophet model. 

Figure 1 shows the search trends forecast from the prophet model.
![mercado search trends](/images/mercadosearchtrends.png)

Figure 2 shows the components of the search trends, highlighting the day of week, time of day, and time of year, trends for mercado searchs
![mercado search trends components](/images/mercadotrendscomponents.png)

### Search Trends Summary
Question: What time of day exhibits the greatest popularity?

Answer: The greatest popularity based on the search data is around 00:00 hrs (midnight)

Question: Which day of week gets the most search traffic?

Answer: # Tuesday, the site has it's highest popularity.

Question: What's the lowest point for search traffic in the calendar year?

Answer: # The lowest point of search traffic is in October

Figure 3 shows the sales trend forecast from the prohet model
![mercado sales trends](/images/mercadosalesprophet.png)

Figure 4 shows the components of the sales trends, highlighting the day of week, time of day, and time of year, trends for mercado sales
![mercado sales trends components](/images/mercadosalestrendscomponents.png)

### Sales Trends Summary
Based on the forecast information generated above, produce a sales forecast for the finance division, giving them a number for expected total sales next quarter. Include best and worst case scenarios, to better help the finance team plan.
Answer: # The current forecast, predicts that sales for the quarter will be most likely be around 970. Worst case, it will be at 887, and best case will be at 1051.