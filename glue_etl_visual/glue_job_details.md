# AWS Glue Visual ETL Job

## Input
- S3 Bucket: `car-pipeline-raw`
- File: `cars_raw.csv`

## Transformation

- Changed the schema`
- Added new column `Car_Age = current_year - Year`

## Output
- S3 Bucket: `car-pipeline-transformed`
- File: `cars_transformed.csv`
