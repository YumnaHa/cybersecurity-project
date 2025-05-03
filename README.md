Project Description:
This project focuses on analyzing cybersecurity vulnerability data from the National Vulnerability Database (NVD), using data science techniques and machine learning algorithms. The aim is to identify common patterns and detect anomalous vulnerabilities that might represent hidden or serious security threats. Python and Google Colab were used to process and visualize the data efficiently.

Data Source:
The dataset contains over 89,000 entries of CVE records, including publication and modification dates, CVSS scores, CWE types, summary descriptions, and various impact/access metrics.

Tools & Technologies:
•	Python
•	Google Colab (online IDE)
•	pandas (data manipulation)
•	matplotlib & seaborn (data visualization)
•	scikit-learn (machine learning models)

Project Structure:
cybersecurity-project/
│
├── Cybersecurity_Analysis.ipynb
├── Yumna Hameed_Siber_Guvenlik_Analitigi_Proje.docx          
├── README.md                          
├── Data.zip
│
├── images/                            
│   ├── Pic1_Importing and Reading the Data.png
│   ├── Pic2_Dataset Overview.png
│   ├── Pic3_Descriptive Statistics.png
│   ├── Pic4_CVSS Score Distribution.png
│   ├── Pic5_Top CWE Visualization Analysis.png
│   ├── Pic6_Categorical Feature Analysis.png
│   ├── Pic7_Analysis of Impact on System Confidentiality.png
│   ├── Pic8_Analysis of Impact on System Integrity.png
│   └── Pic9_CVSS score & CWE code implementation.png

Dataset Information:
•	Dataset: CVE (Common Vulnerabilities and Exposures) records
•	Source: Official CVE database or a structured dataset with vulnerability logs
•	Processing: Cleaned and analyzed to extract trends, severity distributions, affected products, and yearly growth of vulnerabilities
•	Visualizations: Graphs and charts highlight the most frequent CVEs, severity levels, and targets

How to Run the Project:
1.	Open Cybersecurity_Analysis.ipynb using Google Colab.
2.	Upload the CVE dataset manually or mount your Google Drive if it’s stored there.
3.	Run all cells step by step to process the data and generate insights.
   
▶️ [Open in Google Colab](https://colab.research.google.com/github/YumnaHa/cybersecurity-project/blob/main/Cybersecurity_Analysis.ipynb)
⚠️ To run the notebook successfully, please upload the `Data.zip` file (which contains the CVE dataset) to your Colab session.
Download the dataset (Data.zip) to run the analysis notebook.
Output:
•	Summary statistics of CVE entries
•	Charts showing severity levels (Low, Medium, High, Critical)
•	Trends over years (e.g., increase in vulnerabilities)
•	Visualizations of affected software, vendors, or categories

Conclusion:
This analysis provides a clear and practical overview of real-world software vulnerabilities by utilizing publicly available CVE data. By processing over 2,000 entries and examining various severity levels and vulnerability patterns, the study contributes to:
•	A data-driven understanding of prevailing security risks: The analysis leverages real-world data to offer deep insights into the current security threats.
•	The use of the Isolation Forest algorithm to detect outlier threats: By applying this advanced algorithm, the study elevates traditional statistical analysis, transforming it into an intelligent security tool capable of identifying unusual vulnerabilities that may remain undetected in complex environments.

Developer Info:
•	Name: Yumna Hameed
•	Project: CVE Data Analysis for Cybersecurity
•	Platform: Google Colab
•	Language: Python

