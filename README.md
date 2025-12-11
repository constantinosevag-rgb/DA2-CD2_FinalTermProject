# DA2-CD2_FinalTermProject
Data Analysis 2 / Coding 2 Final Term Project Repo 

# The Price of Location: Athens Airbnb Data Analysis

**Course:** Data Analysis 2 & Coding 2  
**Student:** Konstantinos Evagorou  
**Term:** Fall 2025  

## 📌 Overview
This project investigates the relationship between the distance from the city center (Syntagma Square) and the listing price of Airbnb apartments in Athens. The goal is to determine the "location premium" and provide insights for potential investors or travelers.

## 📂 Repository Structure
* `Data/`: Contains the raw dataset (compressed).
* `DA2_Term_Project.ipynb`: The main Jupyter Notebook with analysis and code.
* `DA2_Term_Project.pdf`: The final report in PDF format.

## 📊 Data Source
The dataset was obtained from [Inside Airbnb](http://insideairbnb.com/get-the-data/), specifically the "Detailed Listings" file for Athens.
* **Observations:** ~14,500 listings
* **Key Variables:** Price, Latitude, Longitude, Accommodates, Room Type.

## 🚀 Key Findings
* **Location Penalty:** Moving 1km away from the center results in approximately a **25.7% decrease** in price.
* **Price Distribution:** Prices are highly right-skewed, necessitating log-transformation for regression analysis.
* **Robustness:** The negative correlation between distance and price holds true across multiple model specifications (simple, multivariate, and full controls).

## 🛠️ How to Run
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
