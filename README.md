# 🧪 [Project Name] Test Automation Framework  

# 📌 Overview
"A Selenium WebDriver-based test automation framework for [web name] platform, using Cucumber (BDD) and TestNG for reporting."

# 🛡️ Project Badges

## IDE and Tools
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-2025.2-blue?logo=intellij-idea&link=https://www.jetbrains.com/idea/download/)
![Java](https://img.shields.io/badge/Java-21-blue?logo=java&link=https://www.oracle.com/java/technologies/javase/jdk21-archive-downloads.html)
![Maven](https://img.shields.io/badge/Maven-3.9.9-blue?logo=apache-maven&link=https://maven.apache.org/download.cgi)
![Jenkins](https://img.shields.io/badge/Jenkins-2.462.1-blue?logo=jenkins&link=https://www.jenkins.io/download/)

## Dependencies
![Rest Assured](https://img.shields.io/badge/Rest_Assured-5.5.5-blue?logo=java&link=https://mvnrepository.com/artifact/io.rest-assured/rest-assured)
![TestNG](https://img.shields.io/badge/TestNG-7.11.0-blue?logo=testng&link=https://mvnrepository.com/artifact/org.testng/testng)
![SLF4J Simple](https://img.shields.io/badge/SLF4J_Simple-2.0.17-blue?logo=java&link=https://mvnrepository.com/artifact/org.slf4j/slf4j-simple)
![SLF4J API](https://img.shields.io/badge/SLF4J_API-2.0.17-blue?logo=java&link=https://mvnrepository.com/artifact/org.slf4j/slf4j-api)
![Appium Java Client](https://img.shields.io/badge/Appium_Java_Client-9.5.0-blue?logo=appium&link=https://mvnrepository.com/artifact/io.appium/java-client)
![Extent Reports](https://img.shields.io/badge/Extent_Reports-5.1.2-blue?logo=java&link=https://mvnrepository.com/artifact/com.aventstack/extentreports)
![Jackson Databind](https://img.shields.io/badge/Jackson_Databind-2.19.1-blue?logo=java&link=https://mvnrepository.com/artifact/com.fasterxml.jackson.core/jackson-databind)
![Apache POI OOXML](https://img.shields.io/badge/Apache_POI_OOXML-5.4.1-blue?logo=apache&link=https://mvnrepository.com/artifact/org.apache.poi/poi-ooxml)
![Apache POI](https://img.shields.io/badge/Apache_POI-5.2.4-blue?logo=apache&link=https://mvnrepository.com/artifact/org.apache.poi/poi)
![Allure TestNG](https://img.shields.io/badge/Allure_TestNG-2.29.1-blue?logo=java&link=https://mvnrepository.com/artifact/io.qameta.allure/allure-testng)
![Allure Rest Assured](https://img.shields.io/badge/Allure_Rest_Assured-2.29.1-blue?logo=java&link=https://mvnrepository.com/artifact/io.qameta.allure/allure-rest-assured)
![MSSQL JDBC](https://img.shields.io/badge/MSSQL_JDBC-12.10.1.jre11-blue?logo=microsoft-sql-server&link=https://mvnrepository.com/artifact/com.microsoft.sqlserver/mssql-jdbc)
![Jakarta Mail](https://img.shields.io/badge/Jakarta_Mail-2.0.1-blue?logo=java&link=https://mvnrepository.com/artifact/com.sun.mail/jakarta.mail)
![Zip4j](https://img.shields.io/badge/Zip4j-2.11.5-blue?logo=java&link=https://mvnrepository.com/artifact/net.lingala.zip4j/zip4j)
![Selenium Java](https://img.shields.io/badge/Selenium_Java-4.34.0-blue?logo=selenium&link=https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java)
![Cucumber Java](https://img.shields.io/badge/Cucumber_Java-7.26.0-blue?logo=cucumber&link=https://mvnrepository.com/artifact/io.cucumber/cucumber-java)
![Cucumber TestNG](https://img.shields.io/badge/Cucumber_TestNG-7.26.0-blue?logo=cucumber&link=https://mvnrepository.com/artifact/io.cucumber/cucumber-testng)
![Extent Reports Cucumber Adapter](https://img.shields.io/badge/Extent_Reports_Cucumber_Adapter-1.14.0-blue?logo=java&link=https://mvnrepository.com/artifact/tech.grasshopper/extentreports-cucumber7-adapter)
![Commons IO](https://img.shields.io/badge/Commons_IO-2.17.0-blue?logo=apache&link=https://mvnrepository.com/artifact/commons-io/commons-io)
![Video Recorder](https://img.shields.io/badge/Video_Recorder-1.0.2-blue?logo=java&link=https://mvnrepository.com/artifact/com.automation-remarks/video-recorder)

## Plugins
![Maven Compiler Plugin](https://img.shields.io/badge/Maven_Compiler_Plugin-3.14.0-blue?logo=apache-maven&link=https://mvnrepository.com/artifact/org.apache.maven.plugins/maven-compiler-plugin)
![Maven Surefire Plugin](https://img.shields.io/badge/Maven_Surefire_Plugin-3.5.3-blue?logo=apache-maven&link=https://mvnrepository.com/artifact/org.apache.maven.plugins/maven-surefire-plugin)
![Maven Enforcer Plugin](https://img.shields.io/badge/Maven_Enforcer_Plugin-3.6.1-blue?logo=apache-maven&link=https://mvnrepository.com/artifact/org.apache.maven.plugins/maven-enforcer-plugin)
![Allure Maven Plugin](https://img.shields.io/badge/Allure_Maven_Plugin-2.15.2-blue?logo=java&link=https://mvnrepository.com/artifact/io.qameta.allure/allure-maven)
![Exec Maven Plugin](https://img.shields.io/badge/Exec_Maven_Plugin-3.5.1-blue?logo=apache-maven&link=https://mvnrepository.com/artifact/org.codehaus.mojo/exec-maven-plugin)
![Maven Cucumber Reporting](https://img.shields.io/badge/Maven_Cucumber_Reporting-5.7.0-blue?logo=cucumber&link=https://mvnrepository.com/artifact/net.masterthought/maven-cucumber-reporting)

# 📋 Table of Contents (Optional but Useful for Large Projects)
- [Prerequisites](#-prerequisites)
- [Setup](#-setup)
- [Project Structure](#-project-structure)
- [Running Tests](#-running-tests)
- [Test Coverage](#-test-coverage)
- [Framework Features](#-framework-features)
- [Contributing](#-contributing)
- [License](#-license)


# 📂 Project Structure
📦 repo  
├── 📂 src/main/java  
│   ├── 📂 pages          # 📦 Page Objects Model Classes 
│   ├── 📂 utils          # 🛠️ Helpers (ConfigReader, ScreenshotUtils)  
│   └── 📂 api            # 🌐 API Clients (for RestAssured projects)
│   └── 📂 runners        # 🏃 Test Runners (TestNG/Cucumber)
├── 📂 src/test  
│   ├── 📂 features       # 📑 Cucumber .feature files  
│   ├── 📂 step_defs      # 📝 BDD Steps (Cucumber projects)   
│   └── 📂 test_cases     # ✔️ Traditional Test Classes  
│   └── 📂 resources      # ✔️ Traditional Test Classes  
│       └── 📂 fileA      # ✔️ Traditional Test Classes  
│       └── 📂 config     # ⚙️ Configuration files 
├── 📂 reports            # Test execution reports  
└── 📂 docs               # Additional documentation  


---

## 🛠️ Prerequisites  
| Requirement       | Version/Details                  |
|-------------------|----------------------------------|
| Java JDK          | 11+ (Recommended: 17)           |
| Maven             | 3.8.1+                          |
| Browser/Device    | Chrome 115+ / Android 10+ etc.  |
| Drivers           | chromedriver (matching version) |

---

## 🏗️ Setup & Installation

To clone and build the project, run the following commands:

```bash
git clone https://github.com/Abdullahmostafah/[repo-name].git
cd [repo-name]
mvn clean install
```

# ⚙️ Configuration files:
## config.properties 
**Browser Configuration**
browser=chrome  
url=https://example.com  

# Extent Properties
## extent.properties
**Enable Spark reporter**
extent.reporter.spark.start=true
extent.reporter.spark.out=target/reports/ExtentReport.html

**Configure test name display**
extent.reporter.spark.cucumber.scenario.name=true
extent.reporter.spark.vieworder=dashboard,test,category,exception,author,device

**Report settings**
extent.reporter.spark.documentTitle=Winjigo Test Report
extent.reporter.spark.reportName=Automation Test Results
extent.reporter.spark.theme=standard

**Screenshot settings**
screenshot.dir=target/screenshots/
screenshot.rel.path=../screenshots/


## 🤝 Contributing

1. Fork the repo  
2. Create a branch (`git checkout -b feature/new-feature`)  
3. Commit changes (`git commit -m "Add new feature"`)  
4. Push (`git push origin feature/new-feature`)  
5. Open a Pull Request  
Please ensure your code follows the existing style and includes appropriate tests.

## 📜 License  
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.  
**Note**: Contributions require review via pull requests (direct pushes to `main` are blocked).


## 🧑‍💻 Author
**Abdullah Mostafa** 

For issues or suggestions, contact 
GitHub: [Abdullahmostafah](https://github.com/Abdullahmostafah).

