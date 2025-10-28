# task6
# ☁️ Task 6: Host and Deploy a Web Application on the Cloud (AWS)

## 🎯 Objective

To deploy a simple *web application* on the *AWS Cloud* using *Amazon S3 Static Website Hosting*.  
This task demonstrates how to make a web app publicly accessible and understand real-world cloud deployment workflows.

---

## 🛠️ Tools Used

- *AWS S3 (Simple Storage Service)* – for static website hosting  
- *AWS Management Console*  
- *VS Code / Notepad* – for HTML editing  
- *Web Browser* – for testing the live site  

---

## 📂 Project Files

index.html

### index.html
```html
<!DOCTYPE html>
<html>
<head>
  <title>My Cloud App</title>
</head>
<body>
  <h1>Hello Cloud!</h1>
  <p>This is my first web app hosted on AWS S3.</p>
</body>
</html>


---

🚀 Deployment Steps

1️⃣ Create an HTML Web Page

Created a simple index.html file with a message "Hello Cloud!" using VS Code.


---

2️⃣ Log in to AWS Console

Went to https://aws.amazon.com/console/

Logged in to my AWS account.



---

3️⃣ Open S3 Service

Searched for “S3” in the AWS Console.

Clicked “Create bucket.”



---

4️⃣ Create a New S3 Bucket

Bucket name: my-cloud-app-ashwini

Region: Asia Pacific (Mumbai)

Unchecked: Block all public access

Acknowledged the warning and clicked Create bucket.



---

5️⃣ Upload Files

Opened the bucket → Clicked Upload

Added index.html file

Clicked Upload



---

6️⃣ Enable Static Website Hosting

Went to Properties → Static website hosting → Edit

Selected Enable

Chose Host a static website

Entered:

Index document: index.html


Clicked Save changes



---

7️⃣ Make Files Public

Went to Objects tab → selected index.html

Clicked Actions → Make public using ACL
(If not visible, enabled ACLs under bucket permissions.)



---

8️⃣ Access the Live Website

Copied the Bucket website endpoint under Static website hosting section.

Opened in browser to verify the website is live.


🌐 Live URL Example:
http://my-cloud-app-ashwini.s3-website-ap-south-1.amazonaws.com


---

9️⃣ Verification

✅ Web page loads successfully on browser.
✅ Accessible publicly from anywhere.
✅ Cloud deployment completed using AWS S3.


---

📸 Screenshots

1. AWS S3 Bucket – Static Hosting Enabled


2. Browser – Live Web Page URL


3. AWS Console – Uploaded Files



(Add your actual screenshots here in the GitHub repo images folder)

Example:

![S3 Bucket Screenshot](images/s3-bucket.png)
![Live Site Screenshot](images/live-site.png)


---

🧠 Key Learnings

Understood how to deploy a static website on AWS S3.

Learned how to enable public access safely.

Explored the Static Website Hosting feature.

Learned how to get a public endpoint URL from AWS.



---

💬 Interview Questions

1️⃣ What are the main steps to host a static website on AWS S3?
2️⃣ What’s the difference between S3 and EC2 for website hosting?
3️⃣ How do you make S3 content publicly accessible?
4️⃣ What is the static website hosting feature in S3?
5️⃣ How can you connect your S3 site to a custom domain (Route 53)?
6️⃣ How can you secure access to your S3 bucket?


---

🧹 Cleanup

After testing, delete the S3 bucket to avoid unnecessary usage:

Go to S3 Console → Select Bucket → Delete.



---

🏁 Outcome

By completing this task, I learned how to:

Host a simple web app on AWS S3.

Make it live with a public URL.

Understand the basics of cloud deployment, permissions, and website hosting.



---

👩‍💻 Author: Ashwini Rathod
🔗 GitHub: https://github.com/Ashwinigrathod

---
