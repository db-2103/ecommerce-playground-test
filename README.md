# ecommerce-playground-test
Install Node.js
-   Go to official web and download Node.js as per your system requirement
Double click on downloded file and finish installation

Setting up Envirnment Path
-   Go to c://programfiles/nodejs and copy path
-   Open system envirnment add new environment
-   Value name : NODE_HOME
-   Value path : copy above path

Downlaod visual studio
-   Download and install visual studio

Settingup Playwright framework
-   File>>Create new empty folder(Ex :PlaywrightAutomation)
- Go to termial in VS to download all playwright dependanceies >> npm init playwright

This will create project structure and install all dependancies


-   Playwright.confic.js >> This is test runner file which gives detials like timeout, browser etc here  accordingly scenarios will be executed.
-   package.jason >> This file contains detail of playwright depedancy
-   Create new spec.js with suitable name under 'tests' folder >> use Techtask.spec.js file which has my code for all testcases

After importing script run command in VS terminal
-   npx playwright 
-   test tests/Techtask.spec.js   
 It will run my scenarios and provide details of Testcases

