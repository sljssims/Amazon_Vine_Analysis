# Amazon_Vine_Analysis
### Perform an ETL on selected dataset
Using an amazon url with customer reviews for pet toys for the first deliverable.  The task of extracting the data was completed using the following methods;
- Pyspark was used to read in the CSV file and functions were used to transform and filter the data
- An RDS was created using AWS
- The information extracted and cleaned using Pyspark was loaded into PGAdmin to create a customer, products, review_id and vine table. 

## ![Review Dataset](https://user-images.githubusercontent.com/87907584/143773875-596e554e-eddc-4ff6-8894-8ab68181c06b.png)

## ![Parsed Dataframe](https://user-images.githubusercontent.com/87907584/143773935-a3243e94-3152-416c-a069-ecdf64d91075.png)

## ![customers_df](https://user-images.githubusercontent.com/87907584/143773990-9207d31a-814e-453b-bb25-cd655a5ae69d.png)

## ![products_df](https://user-images.githubusercontent.com/87907584/143774029-13beebbc-8604-49d3-bc49-00c66fde1d1a.png)

## ![review_id_df](https://user-images.githubusercontent.com/87907584/143774056-9cdcf1ac-e1ea-493d-a495-8af18ffc43e3.png)

## ![vine_df](https://user-images.githubusercontent.com/87907584/143774095-a656dc9d-34c9-4012-9849-23dc0e11d564.png)


### Overview Analysis of Vine data to determine if paid reviews are biased
- How many Vine reviews and non-Vine reviews were there? <br>
Total number of reviews was determined to be 38010. <br>
![Total Number of Reviews](https://user-images.githubusercontent.com/87907584/143924731-423b6af8-0da4-4142-b518-c85e5281441d.PNG) <br>
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?<br>
The total number of 5 star reviews was calculated at 20677 with 14950 reviews being vine 5 star reviews and 5727 reviews being non-vine 5 star reviews. <br>
![Total number of 5 star Reviews](https://user-images.githubusercontent.com/87907584/143924741-f3b2c317-4332-45cc-ad58-c85f2624eabb.PNG) <br>
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars? <br>
![Percentage of Vine and Non Vine Reviews](https://user-images.githubusercontent.com/87907584/143924746-f934ac69-4954-41b7-9cba-cfe560746c11.PNG) <br>
## Summary
 - In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. <br> 
Based on the data, there is not a positive bias present for paid reveiws. 54% percent of reviews were five star reviews as previously calculated.  
 - Provide one additional analysis that you could do with the dataset to support your statement. <br>
 If we expanded the dataset to include 4 star reviews as well as include the review of the parent product we could obtain a more specific dataset of individuals to market to.  From a business perspective, this dataset could assist with the new product launch and target individuals who have shown to respond to target marketing due to the inclusion of the 'parent product' variable in the new anlysis. 
