# Regex Matching Web Application

This web application allows users to input a test string and a regular expression (regex), displaying all matches found. It replicates the core functionality of regex101.com using Flask, a Python web framework.

## Features

- Input a test string and a regex pattern.
- View all matches found based on the provided regex.
- Bonus: Validate the validity of an email address.

## Setup and Installation

1.**Clone the Repository:**
git clone https://github.com/your-username/regex-matching-app.git
cd regex-matching-app

2.**Install Dependencies:**
pip install -r requirements.txt

3.**Run the Application Locally:**
Regex.py

4.**Access the Application:**
Open a web browser and navigate to http://localhost:5000

## Deployment on AWS Cloud 

1.**Install and Configure AWS CLI:**
Install AWS CLI if you haven't already: https://aws.amazon.com/cli/

2.**Configure AWS CLI with your credentials:**
aws configure

3.**Initialize Elastic Beanstalk Application:**
eb init -p python-3.x your-application-name
Replace your-application-name with a unique name for your Elastic Beanstalk application.

4.**Create and Deploy the Environment:**
eb create your-environment-name
Replace your-environment-name with a name for your environment.

5.**Access Your Application:**
Once the deployment is complete, you can access your application using the provided URL.

## Usage
1. Input a test string and a regex pattern on the home page.
2. Click "Submit" to view all matches.
3. Optionally, use the email validation feature.
