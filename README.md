# **Gitex Company Scraper and Power BI Analysis**

## **Overview**
This project involves scraping data from the Gitex website to extract company profiles, performing data analysis and exploration, and creating a Power BI dashboard to visualize insights. The key steps include:

1. Extracting company names and details from the website using Python.
2. Normalizing the data for URL generation and extracting detailed information.
3. Performing exploratory data analysis (EDA) to understand company descriptions and identify key trends.
4. Analyzing the likelihood of companies integrating Microsoft's products and services based on specific keywords.
5. Visualizing insights in Power BI for better decision-making.

---

## **Features**
- **Web Scraping:** Automated extraction of company details from Gitex.
- **Data Cleaning & Normalization:** Preparing data for URL generation and downstream analysis.
- **EDA & Keyword Analysis:** Investigating company descriptions and keywords for strategic insights.
- **Microsoft Product Likelihood Analysis:** Calculating probabilities of companies adopting Microsoft's solutions.
- **Power BI Dashboard:** An interactive report for stakeholders to explore the data visually.

---

## **Folder Structure**
```plaintext
.
├── code/
│   ├── # Code for extracting company names from Gitex
│   ├── # Code for cleaning data and extracting detailed profiles
│   └── # Code for EDA and keyword-based likelihood analysis
├── data/
│   ├── # Extracted company data
│   ├── # Cleaned and detailed profiles
│   └── # Final dataset for Power BI
├── visuals/
│   ├── dashboard_preview.png         # Screenshot of the Power BI report
├── Gitex_Report.pbix                 # Power BI report file
├── README.md                         # Project documentation
└── requirements.txt                  # Required Python libraries
```
---

## **Steps to Reproduce**
### 1. **Environment Setup**
- Clone this repository:
  ```bash
  git clone <repository-url>
  cd <repository-folder>
  ```
- Install the required Python packages:
  ```bash
  pip install -r requirements.txt
  ```

### 2. **Extract Data**
- Run the script to scrape company names:
  ```bash
  python code/extract_companies.py
  ```
- Normalize and extract detailed profiles:
  ```bash
  python code/normalize_and_extract.py
  ```

### 3. **Perform Analysis**
- Conduct exploratory data analysis and keyword analysis:
  ```bash
  python code/eda_and_keywords_analysis.py
  ```

### 4. **Move Data to Power BI**
- Prepare the data for Power BI by running:
  ```bash
  python code/move_to_powerbi.py
  ```
- Import `processed_data.csv` into Power BI Desktop.

### 5. **View the Dashboard**
- Open `Gitex_Report.pbix` in Power BI Desktop.
- Interact with the dashboard to explore insights.
  
---
## **Key Insights**
1. **Company Distribution**:
   - Total companies analyzed: 123.
   - Top regions: Africa and Europe.

2. **Keyword Analysis**:
   - Keywords with the highest frequency include "AI," "innovation," and "technology."
   - Likelihood of integrating Microsoft products is visualized using keyword matching.

3. **Stand Info**:
   - Key exhibition stands and halls highlighted for strategic planning.

4. **Descriptions**:
   - Rich descriptions provide insights into company offerings.

---

## **Power BI Dashboard**
![Dashboard Preview](visuals/dashboard_preview.png)
