# Fraud-Analysis-End-to-End-Project
End to End Dummy Project
## Project Overview
This project analyzes transactional data from **January 2023 to January 2025** to identify patterns, risk factors, and concentrations of fraudulent activity across customer demographics, geographic locations, device channels, transaction types, and time periods, to inform targeted fraud prevention strategies. This Project Includes Data Cleaning,Exploratory Data Analaysis(EDA),Data Modelling And Data Visualisation.

---
## Objectives
1. Measure the overall scale and rate of fraud. To determine the total volume and monetary value of transactions, and calculate the overall fraud rate, to establish a baseline against which all other findings can be benchmarked.
2. Identify which demographic groups are most vulnerable to fraud. To examine fraud rates across different age groups and gender categories to determine whether certain segments of the customer base face disproportionately higher fraud exposure, and to understand where protective interventions may be most urgently needed.
3. Assess geographic and branch-level fraud concentration. To compare fraud rates across states and branch locations to identify whether fraud is evenly distributed or concentrated in specific regions, and to determine whether branch-level operational factors may be contributing to elevated risk.
4. Determine which transaction types carry the highest fraud risk. To investigate the distribution of fraud across transaction categories, including wire transfers, ATM withdrawals, peer transfers, and foreign transactions, to identify which channels are most frequently exploited and warrant the strongest controls.
5. Evaluate the role of digital and physical device channels in fraud exposure. To compare fraud volumes across device types, mobile app, web browser, POS terminal, ATM, and phone banking, to understand how fraud risk varies by access channel and identify where technical security investments should be prioritised.
6. Examine temporal patterns in fraud activity. To analyse fraud rates by time of day and by month over the two years, to determine whether fraud is concentrated at particular times of day or shows seasonal and trend-based fluctuations that could inform real-time monitoring and alert thresholds.
7. Track the trend and trajectory of fraud over time. To monitor how the monthly fraud rate has evolved from January 2023 to January 2025, identifying periods of improvement, deterioration, and anomalous spikes that may indicate emerging threats or the impact of existing fraud controls.

---
## Tools Used
Microsoft Power BI	Primary dashboard tool: data modelling, DAX measures, and all visualisations
Power Query (M Language)	Data transformation and cleaning within Power BI
DAX (Data Analysis Expressions)	Calculated measures: fraud rate, total label,  amount bucket, Hotspot_flag, time group
Microsoft Excel	Used for initial data inspection, source file formatting, and exploratory checks before loading into Power BI

---
## Project Structure
```
├── Fraud.csv                # Raw dataset  
├── cleaned fraud.csv        # Cleaned dataset  
├── dashboard.pbix           # Power BI dashboard 
└──power point report.pptx   # power point report
```
---
## Insights
1. Seniors are the most targeted demographic. The 65+ age group records a fraud rate of 6.75%, nearly 3× the overall rate of 3.52% and more than 3× the youngest group (18–25 at 1.96%). This is consistent with broader financial fraud literature where older customers are disproportionately targeted due to lower digital literacy, greater trust, and higher average account balances. All other age groups cluster tightly between 1.96% and 2.33%, making the 65+ spike a clear statistical outlier requiring dedicated intervention.

2. Salem Branch is a critical risk hotspot. Salem Branch leads all locations at 7.78%, and all top five branches (Salem, Nampa, Miami, Spokane, Honolulu) sit in the range of 6.42%–7.78%. The fact that multiple geographically dispersed branches show similarly elevated rates suggests this is not a single localised problem but may indicate systemic issues, shared processes, common third-party vendors, or fraud ring activity that targets multiple branches simultaneously.
   
3. Wire Transfer and Foreign Transactions are heavily exploited. These two categories represent 43.7% of all fraud from just two of six transaction types. Wire transfers in particular are attractive to fraudsters because they are often irreversible once processed, high in value, and harder to dispute. The concentration in these categories strongly supports the case for enhanced verification controls specifically for these transaction types.
   
4. Mobile is the primary attack surface. With 548 fraud cases, Mobile App accounts for over 41% of all device-based fraud. This is consistent with global trends as mobile banking adoption increases without proportional security investment. Web Browser (340 cases) adds another 25.5%, meaning over two-thirds of fraud occurs through digital channels, making mobile and web security the most impactful area for technical controls.

5. Fraud happens around the clock. The near-uniform spread across time periods (19.30%–21.18%) directly challenges the common assumption that fraud peaks at night or during off-hours. This finding has significant operational implications; it means 24/7 monitoring is genuinely necessary and that any fraud detection system that relaxes alerting thresholds during business hours is miscalibrated.

6. January 2025 represents a potential emerging threat. After a sustained decline through 2024, from approximately 3.8% at the start of 2023 to a low of 2.5% in August 2024, the rate spiked sharply to 4.0% in January 2025. This reversal after a prolonged downward trend is a red flag. It may indicate a new organised fraud campaign, exploitation of a newly discovered vulnerability, or a seasonal pattern (January post-holiday period) that warrants immediate forensic investigation.
## Visualization
![Dasboard]<img width="1346" height="746" alt="Screenshot 2026-06-05 130530" src="https://github.com/user-attachments/assets/d22b5c5d-b2f6-42e4-9260-fba3d826c34d" />


## Recommendations
1.Senior customer protection programme. Given the 6.75% fraud rate among 65+ customers, a dedicated protection programme is the most urgent priority. This should include step-up authentication for high-risk transaction types, proactive outbound fraud education, simplified fraud reporting pathways, and optional account activity alerts via SMS or phone call rather than app notifications.

2. Branch-level risk audit for the top 5 locations, Salem, Nampa, Miami, Spokane, and Honolulu, all require immediate operational audits examining staff training, internal controls, physical security, third-party integrations, and local transaction patterns. Where clusters of fraud cases share characteristics (same agent, same time window, same product type), this may indicate internal fraud or organised external targeting that requires escalation beyond standard fraud operations.

3. Enhanced controls on Wire Transfers and Foreign Transactions. Specific controls to implement include: mandatory dual-authorisation for wire transfers above a defined threshold, a mandatory review delay (e.g. 24 hours) for first-time foreign transaction recipients, velocity checks to flag multiple wire transfers within a short window, and real-time customer confirmation via secondary channel before processing.
   
4. Mobile App security investment. With 41% of fraud occurring on mobile, investment in mobile-specific controls will have the highest return on security spend. Priority measures include: biometric authentication as default, device fingerprinting and binding, in-app behavioural anomaly detection, and mandatory re-authentication for any transaction above a set value threshold.

5. 24/7 fraud monitoring model. The uniform distribution of fraud across all times of day requires a genuine round-the-clock monitoring operation with consistent alert thresholds at all hours, not reduced overnight staffing or relaxed daytime detection rules. Automated real-time alerting systems should be calibrated to treat all time periods equally.
   
6. Immediate forensic review of January 2025 spike. A focused investigation should be launched covering all January 2025 fraud cases to identify common characteristics, transaction type, branch, device, customer segment, and geographic pattern. The goal is to determine within 30 days whether the spike represents a new systematic threat requiring a policy response or a statistical anomaly requiring a data quality review.

Author: \[Keren Ethel Obeng]
 Contact: \[(email:kerenetheloebeng@gmail.com)]
 [LinkedIn](www.linkedin.com/in/keren-obeng | [Portfolio](github.com/keren-ethel-obeng)



  
