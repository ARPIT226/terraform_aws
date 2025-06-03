## Checking application working by verifying the user registration through the application


## Step 1: SSH into the Frontend (NGINX) Server

SSH into the NGINX instance:

  
![SSH into NGINX](https://github.com/user-attachments/assets/82b1ee56-e3b3-47ac-b332-85bd20a4e3ab)

---

## Step 2: From NGINX, SSH into the MySQL Server

From the frontend server, SSH into the MySQL server to inspect the database:

  
![SSH into MySQL](https://github.com/user-attachments/assets/8967c52d-2805-4128-9653-e2dcf53ee9a3)

---

## Step 3: Enable MySQL Service

Start and enable MySQL:

  
![Enable MySQL](https://github.com/user-attachments/assets/861d0c35-3a5e-4d36-a3ca-1fb12105693f)

---

## Step 4: Check for Databases

Log in to MySQL and list all databases:

  
![List Databases](https://github.com/user-attachments/assets/fcfd9c0c-d79f-4f59-b301-fe5ff318e801)

---

## Step 5: View Tables in the Application Database

Check for the `auth_user` table:

  
![auth_user Table](https://github.com/user-attachments/assets/bc11754d-40fe-4072-8549-d1fc3082208d)

---

## Step 6: User Registration Verified

The user is registered successfully in the `auth_user` table:

  
![User Registered](https://github.com/user-attachments/assets/9990af7a-bc5a-481c-9268-a834191a3c76)

---






