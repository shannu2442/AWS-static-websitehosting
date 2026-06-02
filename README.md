# AWS Static Website Hosting

## Name:Kotla Shanmukha Rao
## CodTech InternID:CITS812

## Project Overview
This project demonstrates how to host a static website using Amazon S3. The website is designed as a personal portfolio with sections such as Home, About, Projects, and Contact.

The project showcases cloud deployment concepts and static website hosting without using a traditional web server.

---

## Live Website
Website URL:

https://awsstaticwebsite-484279833440-eu-north-1-an.s3.eu-north-1.amazonaws.com/AWS/index.html

---

## Features
- Responsive Portfolio Website
- Home Section
- About Section
- Projects Section
- Contact Section
- Custom CSS Styling
- JavaScript Interactivity
- AWS S3 Static Website Hosting
- Cloud-Based Deployment

---

## Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript

### Cloud Platform
- Amazon S3
- AWS Static Website Hosting

---

## Project Structure

```text
aws-static-website-project/

├── index.html
├── style.css
├── script.js
│
├── images/
│   ├── profile.jpg
│   ├── project1.jpg
│   ├── project2.jpg
│   └── project3.jpg
│
└── README.md
```

---

## AWS Services Used

### Amazon S3
Amazon S3 is used to:

- Store website files
- Host static web pages
- Provide public website access

---

## Deployment Steps

### Step 1
Create an AWS Account.

### Step 2
Open Amazon S3 Service.

### Step 3
Create a new bucket.

Example:

```text
your-portfolio-bucket-name
```

### Step 4
Disable Block Public Access.

### Step 5
Enable Static Website Hosting.

### Step 6
Upload all website files.

### Step 7
Configure Bucket Policy.

### Step 8
Access the website through the generated endpoint URL.

---

## Bucket Policy Used

```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "PublicRead",
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::your-bucket-name/*"
    }
  ]
}
```

---

## Outcome

After deployment, the website will be:

- Publicly accessible through a web URL
- Hosted on AWS Cloud
- Fast and scalable
- Easy to maintain
- Cost-effective static hosting solution

---

## Author

**Shanmukh**

Web Developer | AWS Cloud Learner

---

## License

This project is created for educational and internship purposes.
