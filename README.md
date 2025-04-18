# StudentMangmentBeta0.0SpringCore
A simple standalone Java-based Student Management System built using Spring Framework, following best practices of modular development, dependency injection, and component scanning.

---

## 📁 Project Structure

StudentMngStandalone
├── src
│   └── main
│       └── java
│           └── com
│               └── prince
│                   ├── StudentMngUserInterface.java
│               └── prince.cfg
│                   └── AppConfig.java
│               └── prince.model
│                   └── Student.java
│               └── prince.repository
│                   └── StudentRepository.java
│               └── prince.service
│                   └── StudentService.java
│   └── test
│       └── java
│           └── com
│               └── prince
├── JRE System Library [JavaSE-1.8]
├── Maven Dependencies
├── Referenced Libraries
├── src
├── main
├── test
├── target
└── pom.xml


---

## 🔧 Technologies Used

- Java 8+
- Maven
- Spring Core (IoC, DI, Annotations)
- Spring Context & Component Scanning

---

## 🚀 How It Works

1. `Student` class is a simple POJO model with `roll`, `name`, and `stander`.
2. `StudentRepository` holds students in an in-memory `List`.
3. `StudentService` provides business logic and interacts with the repository.
4. `AppConfig` is the Spring configuration class using `@ComponentScan`.
5. `StudentMngUserInterface` is the main class that:
   - Initializes Spring context.
   - Adds two sample students.
   - Displays all student data.

---

## 🛠️ How to Run

### Prerequisites:
- Java JDK 8 or above
- Maven
- IDE (e.g., Eclipse)

### Steps:
1. Clone or download the project.
2. Open in your IDE as a Maven Project.
3. Build the project with:
   ```bash
   mvn clean install

---
#output
Saved: Student [roll=1, name=Alice, stander=12]
Saved: Student [roll=2, name=Bob, stander=10]
All Students:
Student [roll=1, name=Alice, stander=12]
Student [roll=2, name=Bob, stander=10]


📄 License
This project is for learning and demonstration purposes. Feel free to use, modify, or share with proper attribution.

👤 Author
Prince Pandey.
