# Dmoney-API-Test-Jemeter

## Technology and Tools used in this Project
- JMeter

## Project Scenarios
- Login to User
- Get User List
- Create a User
- Search the Newly Created User by Id
- Search the Newly Created User by Phone Number
- Search the Mewly Created User by Email
- Update the User Phone Number
- Delete the User

## How to run this project:
 - Clone this project [Dmoney-API-Test-JMeter](https://github.com/ahnafahmad/Dmoney-API-Test-Jemeter.git)  or download the .jmx file in the project directory.

## How to Generate Report: 
 Automated dmoney User API using Jmeter where test request added for Login,Get User List,Creating Users,Searching users by Id/Phone Numer/Email, Updating Users and Deleting Users and performed testing for CRUD operations. 
 Steps to run this project:
 - Give the following commands by opening terminal in the project folder to Create Jmeter Report
 ```
jmeter -n -t Dmoney-User-API-Test.jmx -l Dmoney-User-API-Test.csv -e -o Reports
 ```
 
 ## Prerequisite
  - JDK must be installed
  
  ## Jmeter API Report Image
  
  ### Application Performing Index
  
   ![Dmoney-User-API-Test-1](https://user-images.githubusercontent.com/58990500/193663694-f6ebcdde-9aa3-4e8f-8dc6-0223caf563ae.PNG)
       
  ### Summary Report
  
   ![Dmoney-User-API-Test-2](https://user-images.githubusercontent.com/58990500/193663835-6d7f8006-7852-42db-a7c8-1d2fe1dba8bc.PNG)     
        
  ### Project Structure in Jmeter
  
   ![Dmoney-User-API-Test-3](https://user-images.githubusercontent.com/58990500/193664337-617f9690-04d7-4829-96ec-89f3ed9595af.PNG)
        
  ### All Test Cases passed can be viewed from Jmeter Result Tree
  
   ![Dmoney-User-API-Test-4](https://user-images.githubusercontent.com/58990500/193664695-a7fa5542-b008-4aba-a463-b8b55d9f4dae.PNG)
         
  ### Summary Report in Jmeter
       
   ![Dmoney-User-API-Test-5](https://user-images.githubusercontent.com/58990500/193664848-1ee15fd2-5d96-4bae-9cdb-9b59a915802d.PNG)
