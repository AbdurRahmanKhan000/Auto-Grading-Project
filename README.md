# Auto Grading LMS 🎓💻

An automated code evaluation and Learning Management System (LMS) built to streamline programming education. This platform allows instructors to manage coding assignments and provides students with an interactive environment to practice, submit code, and receive immediate, automated feedback.

## 🚀 Core Features

* **Automated Code Execution:** Securely compiles and evaluates student code submissions against predefined test cases (`CodeExecutionService`).
* **Adaptive Learning Engine:** Dynamically adjusts to student performance to provide tailored practice problems (`AdaptiveEngineService`).
* **Role-Based Access Control:** Secure login and registration systems with distinct dashboards for Instructors and Students.
* **Instructor Dashboard:** A centralized hub for educators to create assignments, define test parameters, and monitor student progress.
* **Interactive Practice Arena:** A built-in web interface for students to write, test, and submit code directly in the browser.

## 🛠️ Technology Stack

* **Backend:** Java, Spring Boot
* **Build Tool:** Maven
* **Database:** MySQL (Configured via `application.properties` and `data.sql`)
* **Frontend Template Engine:** HTML5, CSS3 (Thymeleaf/Static Web Templates)
* **Version Control:** Git & GitHub

## ⚙️ Getting Started

### Prerequisites

* [Java Development Kit (JDK) 17+](https://www.oracle.com/java/technologies/javase-downloads.html)
* [Maven](https://maven.apache.org/download.cgi)
* [MySQL Server](https://dev.mysql.com/downloads/)

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/AbdurRahmanKhan000/Auto-Grading-Project.git](https://github.com/AbdurRahmanKhan000/Auto-Grading-Project.git)
Navigate to the project directory:

Bash
cd Auto-Grading-Project/oop-studio-lms/lms
Configure the Database:
Update the src/main/resources/application.properties file with your local MySQL username and password.

Run the Application:

Bash
mvn spring-boot:run
Access the Platform:
Open your browser and navigate to http://localhost:8080.

👨‍💻 Author
Abdur Rahman Khan

Computer Science Undergraduate | Software Developer

University of Engineering & Technology (UET) Peshawar
