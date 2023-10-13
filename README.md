# <div align=center> Calculator App Automation With Selenium Appium </div>

### <div align=center>In this repository, Selenium WebDriver & Appium  are used to automate the Calculator App.</div>

### Tools & Technology used:
- Selenium Webdriver
- Appium
- Android Studio
- Appium Inspector
- TestNG Framework
- Java
- Intellij idea
- Gradle
- Allure

### Prerequisites

- jdk
- gradle
- appium

### How to run this project:
- Clone this project
- Give this following command for checking the connectivity with emulator : ```adb devices```
- Open Appium Server with this following command: ```appium```
- Open Appium Inspector
- Set desired capabilites in json format & click Start Session:
``` 
{
  "platformName": "android",
  "appium:platformVersion": "11",
  "appium:automationName": "UIAutomator2",
  "appium:appPackage": "com.google.android.calculator",
  "appium:appActivity": "com.android.calculator2.Calculator",
  "appium:app": "D:\\apk\\calculator.apk"
}
```
> ```"appium:app"``` apk location in user pc & ```"appium:platformVersion"``` user emulator android version.
- Open ```build.gradle``` file as a project with Intellij IDEA
- Open ```terminal```
- Give this following command: ```gradle clean test```
- For generating Allure Report use these commands: ```allure generate allure-results --clean -output``` & ```allure serve allure-results```

### Allure Report
![screencapture-192-168-0-152-6832-index-html-2023-10-13-14_41_00](https://github.com/Shaishab10/Calculator_App_Automation_With_Selenium_Appium/assets/54171379/c2025045-005f-4600-8c9e-ed7105c5ab9a)
![screencapture-192-168-0-152-6832-index-html-2023-10-13-14_41_17](https://github.com/Shaishab10/Calculator_App_Automation_With_Selenium_Appium/assets/54171379/8596cbd0-13b9-4279-8cb4-0c72ecafaf53)

### Output Video


https://github.com/Shaishab10/Calculator_App_Automation_With_Selenium_Appium/assets/54171379/50c15388-af2c-4f6e-90d8-244d89c50b4c

#### for Better Quality please visit below link
https://drive.google.com/file/d/1tFCg_EpkjwGQTbVh0ppMaL3cqDmPMqQ4/view?usp=sharing

