# Amazon_Ecommerce-Site_Automation
### This is a complete project where an e-commerce site [Amazon.com](https://www.amazon.com/) is automated by writing test suites using selenium-webdriver and TestNg as testing framework.
One modules/page is automated:
- **Search** </br>


Key test cases (total **3**) are automated.

For failed test cases it will take a screenshot aswell at the point of failure. </br>
**The test runner code can be extracted from this:**
[TestRunner](https://github.com/tanvirmitul/Amazon_Ecommerce-Site_Automation/blob/main/src/test/java/testrunner/HomePageTestRunner.java)</br>
### Technology: </br>
- Tool: Selenium Webdriver
- IDE: Intellij IDEA
- Build tool: Gradle
- Language: Java
- Testing Framework : TestNG

### Prerequisite: </br>
- Need to install jdk 1.8, gradle and allure
- Configure Environment variable for jdk 1.8, gradle and allure
- Clone this project and unzip it
- Open the project folder
- Double click on "build.gradle" and open it through IntellIJ IDEA
- Let the project build successfully
- Click on "Terminal" and run the automation scripts

### Run the Automation Script by the following command:
 ```
 gradle clean test 
 ```
- Selenium will open the browser and start automating.
- After automation to view allure report , give the following commands:
 ```
allure generate allure-results --clean -o allure-report
allure serve allure-results

**Below is my overall report:** </br>
![testreportform](https://github.com/tanvirmitul/Amazon_Ecommerce-Site_Automation/assets/59876702/0a193e85-857b-45a4-9890-a535fa633d9d)</br>

![Allure1](https://github.com/tanvirmitul/Amazon_Ecommerce-Site_Automation/assets/59876702/ff4a7d2e-4bb9-46c9-8d81-a7f8b7b18b6b) </br>

![ALLURE2](https://github.com/tanvirmitul/Amazon_Ecommerce-Site_Automation/assets/59876702/371839cc-6041-47d4-9d1e-fc0b9641c4e4) </br>

![ALLURE3](https://github.com/tanvirmitul/Amazon_Ecommerce-Site_Automation/assets/59876702/f63d8e7b-e5e4-446f-b457-a263659d51e9) </br>

- ## **Here is the overall walkthrough of the project:** [Video](https://drive.google.com/file/d/1dDEzeWQv7v89_W7nniw3-7y80huEWrEs/view?usp=sharing) </br>

