# Amazon_Vine_Analysis
### Deliverable 1 (Perform an ETL on selected dataset)
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

### Deliverable 2 (Determine Bias of Vine Reviews)
Using either PySpark, Pandas, or SQL, use the vine dataset to determine if paid five star reviews are biased. 

### Overview of the Analysis of Vine Bias
- How many Vine reviews and non-Vine reviews were there?
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
## Summary
 - In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. 
 - Provide one additional analysis that you could do with the dataset to support your statement.
