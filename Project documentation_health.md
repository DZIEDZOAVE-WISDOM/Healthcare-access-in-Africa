
# Health care access in Africa

I analyzed a healthcare access dataset for 10 African countries as part of my capstone project with Axia Africa. The purpose of this analysis was to uncover meaningful insights that will contribute to improving healthcare access in Africa.



### Authors

- [DZIEDZOAVE WISDOM](https://github.com/DZIEDZOAVE-WISDOM)

 Email: dziedzoavew@gmail.com
# Documentation


Key stakeholder:

Axia africa.

###  Data source
The data was provided by Axia africa, it contains 15 columns and 2000 rows of data on some selected regions in 10 African countries.

### Data cleaning and preparation
I downloaded the dataset from a google drive and imported it into Microsoft Power Bi through power query.
on power query, i checked for these;

1. I checked for Duplicate rows.
2. I also checked if all the columns are in their correct data type.
3. I dropped down each column to see if there are any inconsistencies in the spellings of the records.
4. i checked for NULL values.
5. based on the population, internet availability, and electricity availability columns, i created a calculated cloumn where Urban areas has a Population ≥ 5,000 AND at least one of Electricity or Internet is "Yes" (or both are "No" but population is high, indicating a hub). whiles Rural areas has a Population < 5,000 OR (Population ≥ 5,000 but both Electricity and Internet are "No").
6. For the purpose of analysis, I also created a calculated column where i divided the "Funding received(USD)" column by the "Annual patients visits" column to get "Funding per patient"



after cleaning the data in power query, I closed and applied the steps i have taken.
## Key research questions
1. How does the distribution of healthcare facilities compare between rural and urban regions?
2. Are urban healthcare facilities receiving more funding than rural ones?
3. Are healthcare facilities with higher funding more likely to have shorter emergency response times?
4. Which facility types (hospitals, clinics, health centers) show the highest efficiency in terms of funding per patient 
visit?

5. What are the critical factors preventing equal access to healthcare across different regions?
6. Which policy recommendations can be made to bridge the gap between urban and rural healthcare services? 
7. How can governments optimize healthcare funding allocation to maximize impact in underserved regions?
## DASHBOARDS
![**DASHBOARD**](https://github.com/DZIEDZOAVE-WISDOM/Healthcare-access-in-Africa/blob/main/Dashboard_1.png)


![**DASHBOARD**](https://github.com/DZIEDZOAVE-WISDOM/Healthcare-access-in-Africa/blob/main/Dashboard_2.png)



## INSIGHTS
1. Urban areas have more healthcare facilities than rural areas. Also in terms of healthcare resources, Urban areas have more doctors, nurses and "hospital" Beds than rural areas.

2. Urban centers received $114m of the total funds, which represents 53.5% whiles rural areas received $99m, which represents 46.5%. This statistics indicates that urban facilities receive more funding than rural facilities.

3. For emergency response time, "Clinic" which received the most funding had the lowest emergency response time whiles "health center" which was the second in terms of total funding received recorded the highest emergency response time. it is worth noting that the difference in emergency response time across the 3 facility types are not significant, ranging from the lowest which is 32.1 minutes to the highest which is 32.67 minutes. This indicates that funding may not be a major determinant of emergency response time.

4. In terms of funding per patient, Hospitals were the most efficient. spending $16.35 per person/visit.

5. Nurses are more than Doctors across all regions.

6. Urban areas have access to more electricity and internet than rural areas.

7. Average distance to a health facility for rural areas is 10.66km


## RECOMMENDATIONS
1. Healthcare funding should be directed by the government toward constructing healthcare facilities nearer to rural communities. This will improve people's access to these facilities and eliminate issues related to traveling long distances to reach them. It will reduce death tolls and also increase the inclination of community members to visit these facilities at the slightest discomfort. Additionally, this will reduce emergency response times, thereby improving survival rates.


2. Healthcare funds should be directed by the government to also ensure stable electricity and internet in rural areas, enabling the smooth operation of healthcare facilities and effective communication. As a result, this will enhance the efficiency of medical services, allow for timely consultations and data sharing, and ultimately improve patient outcomes and community trust in the healthcare system.