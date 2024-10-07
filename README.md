spotify data pipeline project is a comprehensive guide for building and deploying a data pipeline using AWS services to access, process, and store data from the Spotify API. This project focuses on extracting the top 100 global songs and storing the data in a structured format in an S3 bucket.

Project Overview
1. The project consists of the following components:
2. Setup S3 Buckets: Create two S3 buckets, one for raw data and another for processed data.
3. Lambda Functions: Deploy the spotify_api_data_extract and spotify_tranformation_load_function.py as AWS Lambda functions. Grant necessary permissions to access the Spotify API and S3 buckets.
    Configure: Set environment variables for Spotify API credentials and S3 bucket details.
    The spotify_api_data_extract function is triggered to fetch data from the Spotify API and store it in the raw data S3 bucket.
    The spotify_tranformation_load_function function processes the raw data, converts it into a .csv files
