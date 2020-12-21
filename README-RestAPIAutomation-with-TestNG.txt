OBJECTIVE:
Create a robust framework to validate REST API's

Pre-requisites:( all latest)
1) Java
2) IntelliJ / Eclipse
3) Maven
4) TestNG

TechStack :
Java with TestNG 

PROGRAM STRUCTURE:
RestAPIDefinitions.java - All API's are defined in this file 
bigHealth_Operations.java - Common java file to invoke the API calls
bigHealth_Main.java - @Test Main class where tests are defined
bigHealth.xml - suite file to input dynamic parameters and execute the test
bigHealth.xlsx - Input from the user

INPUT:
// To provide an input please go to bigHealth.xls
// Enhancement needs to be done
// Due to limited time just covered GET REST API

OUTPUT:
For now we are just printing the output in console
Please refer the path :
1) console output : ConsoleOutput.txt

To Run:
Run via suite
1) Right click on the xml -> Run ( xml will be displayed along with Run)
2) set vm arguments : -Dtestng.dtd.http=true ( if its intelliJ -Make it as in the brackets[ -ea -Dtestng.dtd.http=true ]
3) Trigger Run

