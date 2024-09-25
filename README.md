# Spotify-Pipeline-in-aws
Implement Complete Data Pipeline Data Engineering Project using Spotify

 1. Integrate with Spotify API
- Register at the Spotify Developer Dashboard to get your API credentials.
- Authenticate using OAuth and write functions to extract data from desired endpoints.

 2. Deploy Code on AWS Lambda
- Create a Lambda function in AWS with Python runtime.
- Package your code (including necessary libraries) and upload it to Lambda.
- Set IAM roles for S3 access.

 3. Add Automatic Trigger
- Set up CloudWatch Events to trigger the Lambda function on a schedule to extract data which will be store in s3. (e.g., daily).

 4. Write Transformation Function
- Develop a function to process and transform the extracted data as needed.

 5. Build Trigger for Transformation
- Integrate the transformation logic in the Lambda function to run after data extraction.

 6. Store Files on S3
- Create an S3 bucket structure (e.g., `raw_data/`, `transformed_data/`).
- Save both raw and transformed data in the respective S3 locations.

 7. Build Analytics Tables with Glue and Athena
- Set up a Glue Crawler to catalog your transformed data in S3.
- Use AWS Athena to query the data and create analytics tables.

This streamlined approach gives you a high-level overview of the project flow. 

