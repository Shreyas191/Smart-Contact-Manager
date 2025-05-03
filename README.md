# 📇 Smart Contact Manager

Smart Contact Manager is a web-based application built using **Spring Boot**, **Thymeleaf**, and **MySQL** that allows users to securely manage and access their important contacts anytime, anywhere.

## 🚀 Features

- ✅ **User Registration and Login**  
  Secure signup and login functionality for personalized contact management.

- 📁 **Save Important Contacts**  
  Store names, phone numbers, email addresses, and other details in one place.

- ☁️ **Access Anywhere**  
  Cloud-based system ensures your data is available from any device with internet access.

## 🛠️ Tech Stack

- **Backend:** Spring Boot (Java)
- **Frontend:** Thymeleaf, HTML, CSS
- **Database:** MySQL

## 📷 Screenshots

## 📸 Screenshots

### 🏠 Home
![home](https://github.com/Shreyas191/Smart-Contact-Manager/blob/main/screenshots/home.png)

### 📝 Register
![register](https://github.com/Shreyas191/Smart-Contact-Manager/blob/main/screenshots/register.png)

### ✅ Postlogin
![postlogin](https://github.com/Shreyas191/Smart-Contact-Manager/blob/main/screenshots/postlogin.png)

### ➕ Add Contact
![addcontact1](https://github.com/Shreyas191/Smart-Contact-Manager/blob/main/screenshots/addcontact1.png)

### ➕ Post Add Contact 
![addcontact](https://github.com/Shreyas191/Smart-Contact-Manager/blob/main/screenshots/addcontact.png)

### 📇 Contacts
![contacts](https://github.com/Shreyas191/Smart-Contact-Manager/blob/main/screenshots/contacts.png)

### 🔑 Change Password
![changepassword](https://github.com/Shreyas191/Smart-Contact-Manager/blob/main/screenshots/changepassword.png)



## 📦 Getting Started

```bash
1. Clone the repository
git clone https://github.com/Shreyas191/Smart-Contact-Manager.git
cd Smart-Contact-Manager

2. Create MySQL Database
CREATE DATABASE contactsmanager;

3. Configure application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/contactsmanager
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password

spring.jpa.hibernate.ddl-auto=update
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect

server.port=8282

