# Project: Visualize Data using Amazon QuickSight

In this project, I have explored how to create dynamic visualizations using Amazon S3 and Amazon QuickSight. The project involves analyzing a dataset of best-selling books from Amazon.com.

## Overview

### Tools and Technologies
- **Amazon S3**: Cloud storage service to store and retrieve data.
- **Amazon QuickSight**: Business analytics service to create visualizations and dashboards.
- **CSV**: Data format for the dataset.
- **manifest.json**: Configuration file for the dataset in Amazon QuickSight.

## Step #1: Download the Dataset
- Navigate to [aws-project-dataset](https://github.com/ImAtharva4907/best-selling-books-aws/tree/main/aws-project-dataset) to download the "Amazon Bestseller Dataset" CSV file and the "manifest.json" file.
- Click on "raw" and use `Control+S` (or `Cmd+S` on Mac) to save both files to your computer.

## Step #2: Store the Dataset in Amazon S3
1. **Open the Amazon S3 console.**
   
   <img src="https://github.com/user-attachments/assets/e395fde3-b21b-42fa-a3a8-f25b7927a99f" alt="Amazon S3 Console" width="600" style="display: block; margin: 0 auto;"/>

2. **Click "Create Bucket."**
   
   <img src="https://github.com/user-attachments/assets/86cfbcaf-6eef-4dea-88c1-fef6f6fcd32e" alt="Create Bucket" width="600" style="display: block; margin: 0 auto;"/>

3. **Name the bucket (e.g., `atharva-aws-project1`) and keep the settings as default.**
   
   <img src="https://github.com/user-attachments/assets/e0615ec0-84cc-40a0-b70a-d2742aa21924" alt="Bucket Settings" width="600" style="display: block; margin: 0 auto;"/>

4. **Replace the URL in the `manifest.json` file with the S3 URL of your dataset.**
   
   <img src="https://github.com/user-attachments/assets/57d30cc7-5848-4873-9c8c-06c2f7d19226" alt="Update Manifest" width="600" style="display: block; margin: 0 auto;"/>

5. **Upload the CSV file and the `manifest.json` file into the bucket.**
   
   <img src="https://github.com/user-attachments/assets/b7b2f4bf-6532-43e9-b322-0608ed78aabd" alt="Upload Files" width="600" style="display: block; margin: 0 auto;"/>
   
   <img src="https://github.com/user-attachments/assets/207bd93a-c187-4424-aa79-0aa45be1f23b" alt="Upload Completion" width="600" style="display: block; margin: 0 auto;"/>

## Step #3: Connect S3 Bucket with Amazon QuickSight
1. **Open the AWS management console and navigate to Amazon QuickSight.**
   
   <img src="https://github.com/user-attachments/assets/9394e1cd-ed40-4792-a9cf-b9aa4a0c95f0" alt="QuickSight Console" width="600" style="display: block; margin: 0 auto;"/>

2. **Sign up for a free trial of the Enterprise edition if you don't have an account.**

3. **Select Amazon S3 and tick the box for the S3 bucket you created.**
   
   <img src="https://github.com/user-attachments/assets/99a66db5-39c2-436f-bed3-494fee5b6123" alt="Select S3 Bucket" width="600" style="display: block; margin: 0 auto;"/>

4. **Enter the link to your `manifest.json` file and connect to QuickSight.**
   
   <img src="https://github.com/user-attachments/assets/f0bdc262-c2d3-4a68-929f-1fb69160b981" alt="Connect to QuickSight" width="600" style="display: block; margin: 0 auto;"/>

5. **Select "Interactive Sheet" to start creating visualizations.**
   
   <img src="https://github.com/user-attachments/assets/02ef5d4d-bbd0-4362-a405-6ef87d236204" alt="Interactive Sheet" width="600" style="display: block; margin: 0 auto;"/>

## Step #4: Create Visualizations
- Drag fields into the graph to create visualizations (e.g., Most popular authors).
- Sort, filter, and customize the graphs as desired.
- Experiment with different types of graphs like bar charts, pie charts, line graphs, etc.
   
   <img src="https://github.com/user-attachments/assets/70a6fd31-b746-4761-8fb1-261f3bd8e070" alt="Create Visualizations" width="600" style="display: block; margin: 0 auto;"/>

## Facing Difficulties?
- [Watch Full Video Tutorial - "Visualize Data using Amazon QuickSight"](https://drive.google.com/file/d/1nZiOm7Np_xhq5PDgOqrQ_T6eWu57gUjl/view?usp=sharing)

## Project Completion Time
- Approximately 1-2 hours, depending on the complexity of the visualizations.
