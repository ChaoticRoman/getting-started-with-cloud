# Getting started with cost-effective cloud app deployment

Let's host a simple application processing a file uploaded by user to Python backend that will process it and return zipped result.

Let us have user authentication, per user load limits and simple cloud deployment.

## Solution

* GitHub Pages for frontend
* AWS Lambda or Google Cloud Functions for serverless backend
* AWS S3 or Google Cloud Storage for storage
* Amazon Incognito or Google Firebase for user authentication
* AWS DynamoDB or Google Firebase RTDB for database

## Let's try both Google and AWS stack to compare

GitHub repos:
* AWS: **TODO**
* Google Cloud: **TODO**

## Sample task

* Users are authenticated with username and passwords
* App accepts a CSV file from authenticated user with `X, Y_1, Y_2, ..., Y_N` lines
* App returns output as a zip file with N SVG plots
* There is a per-user-defined limit of usage count per day
