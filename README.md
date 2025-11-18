# Automation_project1
🧪 Selenium Automation Framework – SwagLabs

A fully functional Selenium Web Automation Framework built using:

→ Java (OOP-based)
→ Selenium WebDriver
→ TestNG
→ Page Object Model (POM)
→ Maven
→ Log4j
→ Allure Reports
→ Assertion + Screenshot on Failure
→ CI/CD ready (GitHub Actions / Jenkins)

This project tests the SwagLabs E-commerce Web Application → https://www.saucedemo.com/

🚀 Features

✔ Page Object Model (POM)
✔ TestNG Parallel Execution
✔ Screenshot on Test Failure
✔ Log4j Logging
✔ Assertions
✔ Config file for environment
✔ Clean folder structure
✔ Maven dependency management
✔ TestNG XML test suite
✔ Reports folder

🏗 Folder Structure
src
 ├── main/java/com.prashant.base
 ├── test/java/com.prashant.pages
 ├── test/java/com.prashant.tests
 ├── test/resources
 ├── logs
 ├── screenshots
 ├── reports
 └── utilities

🔧 How to Run Tests
1. Clone the Repository
   
git clone https://github.com/<your-username>/selenium-swaglabs-automation.git
cd selenium-swaglabs-automation

3. Install Dependencies

mvn clean install

4. Execute Test Suite

mvn test

5. Run Using TestNG

testng testng.xml

🧪 Automated Test Scenarios

→ Login Tests
    Valid login
    Invalid login (wrong password)
    Locked out user
    Missing credentials
→ Products Page
    Add item to cart
    Remove item from cart
    Verify product sorting
    Product price validation
→ Cart & Checkout
    Verify added items
    Checkout first name/last name validation
    Complete order

📊 Reports

Allure + TestNG HTML reports stored under:

/reports

🛠 Tools Used

→ Java
→ Selenium
→ TestNG
→ Maven
→ GitHub
→ Allure Reports
→ Log4j
→ WebDriverManager

👨‍💻 Author

Prashant Pal
Devops Engineer | Automation Engineer | QA | Java | Selenium 
GitHub: 
