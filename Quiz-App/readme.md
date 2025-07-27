# Quiz App 🎓

A full-stack **Quiz Application** with:

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Java Spring Boot  
- **Database**: MySQL

---

## 🚀 Features

- Display a list of quizzes
- Dynamically load quiz questions using REST APIs
- Submit and evaluate answers with instant scoring
- Option to reattempt quizzes
- Clean and responsive user interface

---

## 🧪 Technologies Used

- **Frontend**: HTML5 · CSS3 · JavaScript  
- **Backend**: Spring Boot · Spring MVC · Spring Data JPA  
- **Database**: MySQL  
- **Development Tools**: Git · GitHub

---

## 📁 Project Structure

```text
project/
├── Quiz-App/                 # Frontend code
│   ├── index.html
│   ├── styles.css
│   └── app.js
└── Quiz/                     # Backend (Spring Boot)
    ├── src/
    │   ├── main/java/...     # Controllers, Services, Models
    │   └── resources/
    │       └── application.properties
    └── pom.xmlies
└── pom.xml

```
---

## 🛠️ Installation & Setup

### Prerequisites

- Java JDK 11 or newer  
- Maven  
- MySQL (create a database called `quizdb`)  
- Git  
- (Optional) Docker

### Backend Installation

1. Clone the repository and switch to the backend folder:
   ```bash
   git clone https://github.com/K-MOHIT1/project.git
   cd project/Quiz

2. Update src/main/resources/application.properties with your MySQL connection details:
    spring.datasource.url=jdbc:mysql://localhost:3306/quizdb   
    spring.datasource.username=YOUR_DB_USERNAME   
    spring.datasource.password=YOUR_DB_PASSWORD   
    spring.jpa.hibernate.ddl-auto=update   
    spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

3. Build and run the backend app:
    ```bash
   mvn clean package
    mvn spring-boot:run
