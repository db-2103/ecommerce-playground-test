# ecommerce-playground-test

## Install Node.js
-   Go to official web and download Node.js as per your system requirement
Double click on downloded file and finish installation

## Setting up Envirnment Path
-   Go to folder where nodejs is installed example : "C:\Program Files\nodejs"
-   Edit system envirnment variables and add new environment variables
-   Value name : NODE_HOME
-   Value path : copy nodejs path

## Downlaod visual studio
-   Download and install visual studio

## Settingup Playwright framework
-   File --> Create new folder(Ex :PlaywrightAutomation)
-   Go to termial in VS to download all playwright dependanceies
```sh
npm init playwright
```
-   This will create project structure and install all dependancies

## File Details
-   Playwright.confic.js >> This is test runner file which gives detials like timeout, browser etc here  accordingly scenarios will be executed.
-   package.jason >> This file contains detail of playwright depedancy
-   Create new spec.js with suitable name under 'tests' folder --> use Techtask.spec.js file which has my code for all testcases

## Execute Test
-   After importing script run command in VS terminal
```sh
npx playwright 
test tests/Techtask.spec.js   
```
-   It will run test scenarios and provide results

## Test results
- All three test scenarios will pass successfully and html report genrated under test-results folder
- Copy index.html path and check on browser, which will show all hook steps of test run with all the traces.
