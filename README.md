# 🌐 Setting Up a Website on Cloud

This project demonstrates how to host a static website using **HTML/CSS**, configure it with **IIS (Internet Information Services)**, and deploy it on an **AWS EC2 instance**. It's a hands-on showcase of setting up a cloud-hosted web server from scratch — perfect for learners and professionals exploring web infrastructure and cloud deployment.

---

## 🛠️ Technologies Used

- **HTML** – for structuring the webpage  
- **CSS** – for styling (if applied)  
- **IIS** (Internet Information Services) – Windows-based web server to serve the site  
- **Amazon EC2** – cloud-based virtual machine to host the project  
- **Git** & **GitHub** – version control and portfolio sharing

---

## 🚀 How to Deploy or Test

1. **Launch an EC2 Instance (Windows Server)**  
   - Choose appropriate instance type (e.g., t2.micro for testing)
   - Enable RDP and HTTP/S in security group

2. **Install IIS on the EC2 Instance**  
   - Open Server Manager → Add Roles and Features → Select **Web Server (IIS)**

3. **Transfer Project Files**  
   - Use RDP or Git to move `index.html` and related files to:  
     ```
     C:\inetpub\wwwroot\
     ```

4. **Verify Deployment**  
   - Open the EC2 public IP in your browser  
   - You should see your custom website live 🎉

---

## 📸 Screenshots

> _Add screenshots here (e.g., website in browser, IIS dashboard, EC2 config)_

You can drag and drop them into the GitHub repo or use markdown like:

```markdown
![Website Homepage](screenshots/homepage.png)

✅ Status
✔️ Project completed and deployed on cloud 🔒 IIS configured on EC2 📤 Files version-controlled via Git and GitHub

💬 Author
Leonard Phokane 🧑‍💻 GitHub: @leonardphokane
