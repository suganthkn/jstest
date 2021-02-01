# jstest
Javascript test using webdriverio
Steps that i have followed to execute the task:

Installed NodeJS and Visual studio code

Project Setup using following commands
$ mkdir codetest && cd codetest
$ npm init -y

Installed CLI and Webdriverio using following commands
$ npm i --save-dev @wdio/cli

Generated the configuration file using npx command to store webdriver IO Settings
$ npx wdio config -y

Added selenium-standalone to package.json file using below commands
@wdio/selenium-standalone-service": "^6.12.1 in devDependencies
$ npm install @wdio/selenium-standalone-service --save-dev

Created Test Folder using 
$ mkdir .\test\specs

And created a new test file called basic.js
/test/specs/basic.js

To run the file used the below command
npx wdio run wdio.conf.js

Finally the test was successfully runned for one time showing the pass status.
Later it does not work and i was not able to troubleshoot.

I was able to open the browser and verify the title of the "Getting Started" alone.
And i was not able to script the below task:

Click on the development link and further task was not able to complete.
