# Notes Management REST API

A backend RESTful API for managing notes built using **Spring Boot, MySQL, JPA, and Hibernate**.
This application allows users to create, read, update, and delete notes through REST APIs.

---

## 🚀 Features

* Create a new note
* Retrieve all notes
* Retrieve a note by ID
* Update an existing note
* Delete a note
* RESTful API architecture
* MySQL database integration

---

## 🛠️ Tech Stack

* **Java**
* **Spring Boot**
* **Spring Data JPA**
* **Hibernate**
* **MySQL**
* **Maven**
* 
---

## ⚙️ Setup & Run

### 1️⃣ Clone the repository

```
git clone https://github.com/Saherishkazi/Notes-management-rest-api.git
```

### 2️⃣ Create MySQL Database

```
CREATE DATABASE easy_notes;
```

### 3️⃣ Configure database

Open:

```
src/main/resources/application.properties
```

Update credentials:

```
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD
```

### 4️⃣ Run the application

```
mvn spring-boot:run
```

Application will start at:

```
http://localhost:8080
```


## 🧪 Testing APIs

You can test APIs using:

* Postman
* Thunder Client
* cURL

Example request body:

```
{
  "title": "My First Note",
  "content": "Learning Spring Boot"
}
```

---
**Saherish Kazi**
