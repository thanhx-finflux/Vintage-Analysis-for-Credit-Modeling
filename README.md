# Vintage-Analysis-for-Credit-Modeling
This project is a comprehensive Vintage Analysis of LendingClub consumer loan data from Kaggle to understand credit performance across years and loan terms.

Vintage analysis is a core technique in credit monitoring, portfolio analytics, and underwriting evaluation.

Building vintage curves
- Cumulative default rate
- Months since loan
- Cohorts: 2012-2018
  
## Key Question Answered
- How do default rates evolve as loans age?
- How do vintages differ in the early months from the late periods?
- Which years were high-risk, and which saw underwriting improvements?
- How do structural credit changes show up in the vintage curves?
  
<img width="1153" height="699" alt="Image" src="https://github.com/user-attachments/assets/df9216cb-741a-4444-9fee-1ac984b770fc" />

<img width="903" height="699" alt="Image" src="https://github.com/user-attachments/assets/38f8ab99-65cd-4139-9f79-41c9eae855f5" />

### Key Observations from 2018 Vintage Analysis Heatmap
- In the early months of 2018, cumulative default rates rose sharply, reaching over 4% by month 12 for the January, February, and March cohorts. Indicating lower underwriting standards or economic challenges during that period.
- Middle of the year cohorts (April to August) show more moderate default rates, peaking around 2-3%. This suggests some improvement in loan performance as the year progressed.
- Later cohorts (September to December) have significantly lower default rates, staying below 1% in the first few months. This could be due to shorter observation periods or improved credit risk management.

  
<img width="1813" height="1238" alt="Image" src="https://github.com/user-attachments/assets/64161083-b5e8-4d67-a229-2605c311f682" />

<img width="1510" height="1238" alt="Image" src="https://github.com/user-attachments/assets/3a12a958-c012-4aec-906e-9a920acb2f79" />

- In 2017, it was worse than 2018, with higher cumulative default rates (8-11%)
- In early 2018, improved underwriting standards or economic conditions led to lower default rates compared to 2017.
- Mid 2018, underwriting strengthened further, resulting in even lower default rates, dropping to 1.5-2.5%
- Late 2018, the strongest borrower profiles and tightened credit policies led to minimal defaults, with rates below 1%.

<img width="1608" height="1238" alt="Image" src="https://github.com/user-attachments/assets/7cc691d9-2b30-4065-896c-086d18de6d41" />

<img width="988" height="699" alt="Image" src="https://github.com/user-attachments/assets/8fa0dd95-9cd8-46f4-b085-84f366011ee4" />

<img width="887" height="391" alt="Image" src="https://github.com/user-attachments/assets/6a3654d6-af1c-4968-9626-230bd09f90d1" />

- The graphs show that cumulative default rates in 2016 and 2017 are significantly higher than in other years, indicating that loans issued during these years had a higher risk of default within the first 12 months.
- Overall, the vintage age of Lending Club loan originations from 2012 to 2018 shows a clear risk cycle. Default rose steadily from 2013 to peak in 2016, then declined through 2018, driven by economic conditions and underwriting changes. 2017 remained elevated before a sharp improvement in 2018. In 2018, vintage cohorts exhibited the lowest cumulative default rates in early months, reflecting stronger credit quality and risk management practices.

<img width="1423" height="391" alt="Image" src="https://github.com/user-attachments/assets/268d1939-b3bd-434a-b727-6bf73962b6bb" />

- Default rate at month 36 rises significantly between 2013 and the peak in 2016 and 2017, indicating higher long-term credit risk for loans issued during these years. The worst vintages are 2016 and 2017, with cumulative default rates exceeding 16-17% by month 36.
- Post-2017 vintages show marked improvement, with 2018 cohorts exhibiting the lowest long-term default rates, 4% by month 12, and 4.6% by month 14. This reflects enhanced underwriting standards and risk management practices implemented by Lending Club during this period.

## Key finding
- From 2011 to 2018, the cumulative default rates for loans issued in each month show a general trend of decreasing default rates. This indicates that Lending Club's loan portfolio has improved in quality over time, likely due to better underwriting practices, risk assessment.
- In 2018, the cumulative default rates are significantly lower compared to previous years. For example the average loans issued in 2012 had a cumulative default rate of about 6% after 12 months, while loans issued in 2018 had a cumulative default rate of approximately 2% after the same period. This suggests that Lending Club has been successful in reducing credit risk in its loan portfolio over the years.

## Tool Used
  - Python
  - Pandas, Numpy
  - Matplotlib, Seaborn
  - Jupyter Notebook
 
 ## Contact

Thanh Xuyen, Nguyen

LinkedIn: [xuyen-thanh-nguyen-0518](https://www.linkedin.com/in/xuyen-thanh-nguyen-0518/)

Email: thanhxuyen.nguyen@outlook.com   
