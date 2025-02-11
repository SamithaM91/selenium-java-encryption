# 🚀 Selenium Java Test Automation with Encrypted Annotations

## 🔹 Overview
This project demonstrates Selenium Java Test Automation with **encrypted annotations** to securely manage sensitive data such as passwords.  
It includes:
- **Selenium WebDriver** for browser automation.
- **TestNG** for structured test execution.
- **Encrypted Annotations** to protect sensitive data.
- **Page Object Model (POM)** for organized test scripts.
- **Maven** for dependency management.

## 🔹 Setup Instructions

1️⃣ Prerequisites**
- Install **Java JDK 11+**
- Install **Maven**
- Install **Google Chrome**
- Install **Visual Studio Code** or **IntelliJ IDEA**

2️⃣ Clone This Repository

    git clone https://github.com/SamithaM91/selenium-java-encryption
    cd selenium-java-encryption

3️⃣ Install Dependencies

       mvn clean install
 
4️⃣ Using Encrypted Annotations
To store encrypted passwords, use the EncryptionUtil.java class

    String encryptedPassword = EncryptionUtil.encrypt("yourpassword");
    System.out.println(encryptedPassword);

Store the encrypted value in TestData.java

    @Encrypted
    public static String password = "9Zw8hh+IbW+ls1efFLxWqQ=="; // Encrypted value

5️⃣ Running Tests

    mvn test
Or directly from IntelliJ/VS Code.
