# Hackerrank-Automation
I wrote a script using puppeteer which automates the process of login and adding multiple moderators to multiple contests in hackerrank. The purpose of writing this script was to get familiar with automation and async-await in JavaScript, while having a little fun. 

# Tech-Stack Used
 - JavaScript
 - Libraries used
    - Minimist -> Used to take command line argument
    - Puppeteer -> Used to automate browser

# Features And Functions
Application is able to login provided username and password, and add multiple moderators to multiple contest present in different pages.
Whole process is done using puppeteer library by using it's default chromium browser.

# Key Learning
 - async await function
 - Use of CSS selector

## To Run this project on Local machine
First fork this to your profile, then clone it to your desktop

Change config.json file
```json
{
    "userid": , // add your username 
    "password": , // add your password
    "moderators": [ ] // provide list of moderators to add
}
```
   
Then install libraries 
```bash
npm install minimist
npm install puppeteer 
```
To run this project use this command

```bash
node HackerrankAutomation.js --url=https://www.hackerrank.com --config=config.json 
```
