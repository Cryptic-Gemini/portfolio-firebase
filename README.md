# portfolio-firebase


Firebase Hosting
-------------------

Firebase hosting is a simple, fast, secure & free hosting service provided by Google to deploy static websites that does not involve heavy data processing or any form of complex user authentication requirements. Firebase also provide hosting support with a custom domain with Free SSL certificates.


Prerequisite:
---------------

A Google Firebase account

Scenerio:
-------------

We are deploying a Portfolio on Firebase.


1-Install Firebase CLI:
------------------------

 Install the Firebase CLI using the automatic install script:


$ curl -sL https://firebase.tools | bash

2-Clone a Portfolio:
----------------------

Clone a index.html file fromGithub.

https://github.com/Cryptic-Gemini/Portfolio.git

 
 3-Google Firebase account:
 -----------------------------

Sign in to firebase.google.com using your Google account & Click on Go to console.


4-Create a Firebase project:
--------------------------

Click on Add project and create your firebase project by entering the name of your project.
In my case it is gzl-khan.




 5-Log In to Firebase:
-----------------------

Switch to the project directory (as firebase-app) and open the terminal to run the command:

                         firebase login


6-Initialize Your App:
------------------------
In my case I have a project directory as firebase-app that has a sub directory public.Its a folder that contains all assets to keep app up and running on firebase hosting service.
Switch to the project directory (as firebase-app) and run the command:

                           firebase init
                           
- Use arrow keys to select hosting. Press Spacebar to select features, then Enter to confirm your choices.

- Then it will ask you to select your project.Use arrow keys to navigate to your project name and press enter.

* **Note : If you are not getting the project list in Project setup , then use the command firebase use --add after step 5 & then proceed to step 6 again.

It will ask you to select your project and set an alias for your project.

? Which project do you want to add? portfolio-demo-5979c

? What alias do you want to use for this project? (e.g. staging) default

- It will ask you to confirm the name of your distribution folder.In our case we have a distribution folder as public.

- Answer the rest questions with No as It will try to override your index.html file

- Finishing project setup creates a firebase.json settings file in the root of your project directory.

7-Deploy Site:
---------------------

Let’s deploy the site with command:

                      $firebase deploy

- Done! Copy Hosting URL and paste it in the browser.Your app is running as :

https://gzl-khan.firebaseapp.com/


- You can check your domain by clicking your project and then Hosting from the left panel.









----------------------------------------------------------------------------------------------------------------------------
Summary:
Deployment of portfolio on firebase
---------------------------------------------------------------------------------------------------------------------------

Prerequisites
NodeJS and NPM


STEPS:

Reference= https://firebase.google.com/docs/hosting/quickstart

Before you begin:

Before you can set up Firebase Hosting, you need to create a Firebase project.

Go to https://console.firebase.google.com/ and create a new project

Step 1: Install the Firebase CLI

(cmd: curl -sL https://firebase.tools | bash)

Ref = https://firebase.google.com/docs/cli#install-cli-mac-linux


Step 2: Initialize your project

To connect your local project to your Firebase project, run the following command from the root of your local project 

directory:

 $firebase init

Step 3: Deploy to your site

To deploy to your site, run the following command from the root of your local project directory:

 $firebase deploy


Note:

Follow these links to get more help

https://www.youtube.com/watch?v=shh8K-oq1kA&feature=youtu.be (video for guidance)
https://www.tutorialspoint.com/firebase/index.htm (tutorial )









