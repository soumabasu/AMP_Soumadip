
## Framework Setup
•	Clone the github repository from https://github.com/soumabasu/AMP_Soumadip.git

•	Open the folder in Visual Studio Code

•	Install all the npm packages listed in package.json using the below mentioned command
  npm i --force

## Environment Setup
•	Create a .env file inside your framework directory.

## Please add This below mentioned environment details in .env file to execute the test
## Environment Details
ENVIRONMENT=deloitte

ENVIRONMENT=QA

## Execution Parameters
SPEC_NAME=## Provide the feature file path here

RUN_LIGHT_HOUSE_TEST=false

## LOG_LEVEL
LOG_LEVEL=info

## Drivers
CHROME_DRIVER=latest

FIREFOX_DRIVER=latest

MICROSOFT_EDGE_DRIVER=latest

## Reports Directory
REPORTS_DIR=testResults

RUN_LIGHT_HOUSE_TEST=false

LOG_FILE_DIR=testResults/logs

## Select web browser and device to run test
BROWSER_NAME=chrome ##Change browser name here

DEVICE_NAME= Macbook Pro 15 ##The device name where the test is being conducted must be inserted here


## Select mobile os to run test(example: android or iOS)
PLATFORM_NAME=iOS

## Android Real device capabilities(Change this capabilities as per the current test device and application)
ANDROID_VERSION=13

ANDROID_APK_PATH=/Users/soumabasu/Desktop/pedometer.apk

ANDROID_DEVICE_NAME=Samsung Galaxy S21 Ultra 5G

ANDROID_DEVICE_ID=R5CT3286WBK

APP_PACKAGE= com.olacabs.customer

APP_ACTIVITY= com.olacabs.customer.ui.SplashActivity

## iOS Real device capabilities(Change this capabilities as per the current test device and application)
IOS_DEVICE_NAME=iPhone 13

IOS_VERSION=16.4

UDID=00008110-000C4CA8349A401E

## Provide the webdriver agent path here
WEBDRIVERAGENT_RUNNER=/Users/username/WebDriverAgent/WebDriverAgent.xcodeproj


## Android apk file details
Playstore link of the apk file is https://play.google.com/store/apps/details?id=com.divinememorygames.pedometer
