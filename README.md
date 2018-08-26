# Building MiraHubDroid Mobile App w/ ionic Framework
<img src="https://github.com/7appsinc/MHubDroid/blob/master/www/images/screenshots/mirahub_poster.png">

1. ### Install Node.js
   You must have **Node.js** installed on your system to begin building our app. Please follow the following step if nodejs is not installed on your system. If already done, you can skip this step

        Note: Install Node.js version 8 or above on your system.

   Download the Node.js as per your operating system from [https://nodejs.org/en/download/](https://nodejs.org/en/download/)
   To ensure that you have correct version of nodejs installed, from the command line issue the following command
   ```
   node -v
   ```
   If you see the string containing version number greater than 8, you are good to go. If you get `command not found error`, that means nodejs is not properly installed on your system. You'll need to troubleshoot the problem.
   ###### **You  may be able to use node version lessser than 8 but we haven't tested the app with these versions**


2. ### Install ionic and cordova
   In order to build our app you need to have installed ionic and cordova on your system. To install these packages issue the following command from command line:

        npm i -g ionic@latest

    This will install the ionic and cordova programs on your system. To ensure that you have successfully installed both the programs, issue following command from the command line

        ionic -v && cordova -v

    If version number gets printed on the console, you are good to go. If you get `command not found error`, that means that these programs didn't get properly installed on your system. You'll need to troubleshoot the problem.

    **Make sure you do not accidentally install ionic-v4(beta)**
    
3. ### Screenshots
    
<img src="https://github.com/7appsinc/MHubDroid/blob/master/www/images/screenshots/Screen%20Shot%202018-08-26%20at%208.28.36%20AM.png">
<img src="https://github.com/7appsinc/MHubDroid/blob/master/www/images/screenshots/ionlab.png">
<img src="https://github.com/7appsinc/MHubDroid/raw/master/www/images/screenshots/3.png">
<img src="https://github.com/7appsinc/MHubDroid/raw/master/www/images/screenshots/4.png">
<img src="https://github.com/7appsinc/MHubDroid/raw/master/www/images/screenshots/6.png">
    
4. ### Production build
   To run or build your app for production, run:

        ionic cordova run android --prod --release
        or 
        ionic cordova run ios --prod --release
 

    Voila Your Ready Made BoilerPlate Was Chef Crossfully Safe by JustEd-7AppsInc(Asia)| 7appsinc@gmail.com
