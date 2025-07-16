# 🌐 Static Website Hosting on AWS using S3

This project demonstrates how to host a static website using Amazon S3, one of the most popular cloud storage solutions provided by AWS.

---

## 🚀 Project Overview

A static website (HTML, CSS, JS) is hosted directly on AWS S3, making it highly available, scalable, and cost-efficient. The project includes:
- Hosting setup
- Public access configuration
- Static website endpoint access
- Notes on future improvements

---

## 🧠 Concepts Covered

- ☁️ **Cloud Computing** basics
- 🗂️ **Amazon S3 Buckets & Objects**
- 🧾 **Static vs Dynamic Websites**
- 🔒 **Access control using ACLs**
- 🌐 **Static Website Hosting in AWS**
- 📈 **Monitoring & Logging with CloudWatch**

---

## 🛠️ Tools & Technologies

- **Amazon S3**
- **AWS Console**
- **HTML / CSS / JS**
- *(Optional: CloudFront, Route 53)*

---

## 📝 Step-by-Step Guide

1. **Create an S3 Bucket**
   - Unique name and region selection

2. **Upload Website Files**
   - HTML/CSS/JS files added via AWS Console

3. **Make Files Public**
   - Enable ACLs and remove “Block Public Access”

4. **Enable Static Website Hosting**
   - Set index.html and error.html
   - Copy the generated endpoint

5. **Test Your Website**
   - Open the endpoint URL to view the live site

---

## 🧪 Result

The website is now available at the S3-generated public endpoint. This demonstrates end-to-end static website hosting without any web server setup.

---

## 🔐 Advanced Features (Future Scope)

- Setup **HTTPS** with CloudFront
- Connect **custom domain** via Route 53
- Add **CI/CD pipeline** using GitHub Actions
- Integrate **monitoring and versioning**
- Add **data lifecycle rules** and **replication**

---

## 📷 Screenshot

*(Insert image of website hosted on S3 here)*

---

## 📚 References

- [Amazon S3 Docs](https://docs.aws.amazon.com/s3/index.html)
- [Hosting a Static Website](https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteHosting.html)
- [AWS CloudFront for HTTPS](https://aws.amazon.com/cloudfront/)

---

## 🧑‍💻 Author

**Varshinii Kasirajan**  
B.E. Computer Science & Engineering  
Sathyabama Institute of Science and Technology  
Reg. No: 401114395

---

## 📌 License

This project is for academic learning purposes only.
