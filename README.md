AWS Static Website Hosting

Project Overview
This project demonstrates how to host a static website using "Amazon S3".  
The website is designed as a personal portfolio with multiple sections such as Home, About, Projects, and Contact.  

It showcases cloud deployment concepts using "AWS S3 Static Website Hosting" without using any traditional backend server.

Live Website

Website URL:  
https://awsstaticwebsite-484279833440-eu-north-1-an.s3.eu-north-1.amazonaws.com/AWS/index.html

Internship Details:

Name:Kotla Shanmukha Rao

CodTech Intern ID: CITS812

Features
- Responsive Portfolio Website  
- Single Page Navigation (SPA style)  
- Home Section with Profile Image  
- About Section  
- Projects Section with Images  
- Contact Section  
- Custom CSS Styling  
- JavaScript Interactivity  
- Fully Static Deployment  
- AWS S3 Hosting  

Technologies Used
Frontend
- HTML5  
- CSS3  
- JavaScript  

Cloud Platform
- Amazon S3
- AWS Static Website Hosting  

Project Structure
aws-static-website-project/

├── index.html

├── style.css

├── script.js

│
├── images/

│   ├── profile.jpg

│   ├── project1.jpg

│   ├── project2.jpg

│   ├── project3.jpg

│   └── project4.jpg
│
└── README.md

AWS Services Used
Amazon S3
Amazon S3 is used to:
- Store website files  
- Host static web pages  
- Provide public access to website

AWS S3 Deployment Steps

Step 1
Create an AWS Account.

Step 2
Open Amazon S3 Service.

Step 3
Create a new bucket.
Example:
awsstaticwebsite

Step 4
Disable Block Public Access.

Step 5
Enable Static Website Hosting.

Step 6
Upload all website files:

index.html

style.css

script.js

images/

Step 7
Configure Bucket Policy.

Step 8
Access the website through the generated endpoint URL.



Bucket Policy Used

{
  "Version": "2012-10-17",
  
  "Statement": [
    {
      "Sid": "PublicRead",
      
      "Effect": "Allow",
      
      "Principal": "*",
      
      "Action": "s3:GetObject",
      
      "Resource": "arn:aws:s3::awsstaticwebsite-484279833440-eu-north-1-an /*"
    }
  ]
}
