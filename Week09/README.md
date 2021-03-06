## Web Security: Week 09 HoneyPot

## Time Spent: < 5 Hours

## Objective:
   Learn about Network Security by attacking and being attacked vulnarable networked resources. For this purpose three honeypots were created.

## Google Cloud and Honeypot Setup:
   Google cloud is used to create three honeypot VM ( Ubuntu trusty). MHN server was intalled on mhn-admin VM while other three are being used as honeypot for attacks.
   ![](https://github.com/ahamedbashir/WebSecurityCodepath/blob/master/Week09/Honeypot_VM.gif)
 
## Deploy Script for Dionaea with HTTP
![](https://github.com/ahamedbashir/WebSecurityCodepath/blob/master/Week09/deployScript.gif)
  
## NMAP attack
   nmap is used to attack my own honeypot.
  
## Honeypot Live attack GIF
![](https://github.com/ahamedbashir/WebSecurityCodepath/blob/master/Week09/week9.gif)

## Attack Report json file
   [session.json](https://github.com/ahamedbashir/WebSecurityCodepath/blob/master/Week09/session.json)

## Issues Encountered:
   The issue that most frequently faced is the session timeout while trying to install MHN admin application. The installation would go half way with some of the parameters set and halt in the middle giving me the message of connection time out. The next time the install command is run, the already set parameters would interfere with the new installations and give some error messageses including database error. The issue was resolved by removing VM instance from the Google cloud and everything else from the host including gcloud and redo the setup instructions again.
   I also faced problem to restart the admin console sometime.
    
## Statistics of Attacks
![](https://github.com/ahamedbashir/WebSecurityCodepath/blob/master/Week09/attack%20summery.png)
