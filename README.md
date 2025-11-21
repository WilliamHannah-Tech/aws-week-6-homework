# **Week 6 Homework 📚

_Windows installation + Terraform project setup_

---

## **1. What You Need**

- Windows 11 (64-bit)
    
- PowerShell **Run as Administrator**
    
- Internet connection
    
- Chocolatey (package manager)
    
- VS Code (Terraform editor) 
    
- Git (optional but recommended)
    

---

## **2. Install Chocolatey** 🍫

### **Download the Automation Scripts**

1. Go to: **[https://github.com/rofoed01/scripts_chocolatey](https://github.com/rofoed01/scripts_chocolatey)**
    
2. Click **Code → Download ZIP**  🤐
    
3. Extract the ZIP (Windows Extract or 7-Zip)
    

### **Run Install Scripts** 🏃

- Open the extracted folder
    
- Follow the included instructions
    
- Run scripts **as Administrator**
    
- Allow SmartScreen → _More Info → Run Anyway_
    
- Install time: ~30–45 minutes
    

### **Verify Install** 🔎

`choco list`

---

## **3. Install Terraform, Git, and VS Code**

Run in PowerShell (Admin):

`choco install terraform -y choco install git -y choco install vscode -y`

**Check Terraform:**

`terraform -version`

---

## **4. Create Your Homework Folder & Files**

`cd C:\Users\Willi_so151lg\TheoWAF\class7\AWS\Homework\ mkdir week-6-homework cd week-6-homework touch 0-authentication.tf 1-vpc.tf A-backend.tf .gitignore code .`

---

## **5. Example Terraform Files**

### 0-authentication.tf

### 1-vpc.tf

2-backend.tf


---

## **6. .gitignore 

`**/.terraform/* *.tfstate *.tfstate.* *.tfvars crash.* .terraform.lock.hcl`

---

## **7. Terraform Commands to Run**

`terraform init terraform fmt terraform validate terraform plan terraform destroy`

---

## **8. Git Setup (Optional)**

`git init git add . git commit -m "initial commit"`

---

## **9. Required Screenshots**

- Successful `terraform apply`
    
- Successful `terraform destroy`
    
- `aws authentification`
    
- Your `.gitignore` file

 Terraform installation 