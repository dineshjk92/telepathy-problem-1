# Find Meeting Rooms

## **Problem Statement**

**This is a solution for the problem to find number of meeting rooms required given the meeting time slots.**

**Input:** 

A file contains list of meeting time slots in 24hr format

Input data requirements/assumptions:
* All times in 24hr format
* No meeting ends after midnight (no later than 23:59)
* Since no meeting ends after 23:59, it is assumed that all time slots represents same day
* Meeting time slots need not to be in ascending order


**Output:**

An integer representing number of meeting rooms required

## How to Build:

Build the project from the root directory using the following command

`mvn clean install -U dependency:copy-dependencies`

Once the build is successful, there will be app.jar file in the below path

`telepathy-problem-1/target/app.jar`

## To Execute the program

To execute the program, it requires input file location as an argument

Run the below command from the app.jar folder

`java -jar app.jar "C:\input.txt"`




