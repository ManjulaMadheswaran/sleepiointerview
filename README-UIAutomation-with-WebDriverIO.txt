OBJECTIVE:
Create a robust framework to validate End to End flow with all the scenarios in each Page

Pre-requisites:( all latest)
1) Node.js
2) Visual Studio Code

TechStack :
WebdriverIO with cucumber framework

INPUT(features files):
1) selectDifferentOptions.feature - 1 sample end to end flow till the sign up page 
2) verifyOnboardingQuestions.feature - 1 sample test for q question with multiple conditions

PROGRAM STRUCTURE:
PageObjects 
1) landingpage.js 
2) page.js 
3) questionairePage.js

step-definitions 
1)steps.js

testData
1) common.json - url to launch
2) options.json - value to be selected during the end to end flow
3) questions.json - possible answers for each questions and title( I have added an example for 1 question)

OUTPUT:
Refer SampleOutput.txt

To Run:
Go to the location where we have wdio.conf.js and type 
"npm install && npm test"


