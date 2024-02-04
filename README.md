# Student_Enrollment_Form
## Description 
This is a web based html form for student enrollment using JsonPowerDB as Database with JavaScript and Bootstrap
JsonPowerDB is used to perform CURD operation 
JavaScript as backend
Bootstrap as frontend

* JsonPoweDB http://api.login2explore.com:5577/

# Benefits of using JsonPowerDB
* Simple to use , real time database
* Easy to establish connection between client and server
* Simplest way to retrieve data in a JSON format.
* Backends code is not required for database 
* No need for defining schema 
* Querying the database is easy there is no need  of knowledge of SQL commands

# TECH STACK USED
* HTML
* CSS
* JAVASCRIPT 
* JsonPowerDB ( As Database)

# Screenshots:
<img src="./images/Data.png">
<img src="./images/DataBase.png">

# Illustrations:
* **SAVE** : If student roll number is not existed in database then we can fill other field and save in database
* **UPDATE** : when student roll number is already present in database then student information is fetched from database and filled in respective feild then user can UPDATE student information 
* **RESET** : By this we can clear all field of form and with this except first field (roll-no) other field are disabled until user enter any roll number
* **ALERT** : This website uses disposable Alter prompt using bootstrap

# HOW TO USE

* **Initially**
<img src="./images/Initial_Form.png">

We need to enter roll number field first and after it will check if it is already present on the database or not

* **Fetching student data using roll number**

If it is not present in the database,then enter all other details

<img src="./images/Roll_No_12_Saving.png">

  Now save the data in the database by clicking on Save button and it will automatically reset the page

  <img src="./images/Roll_No_12_Saved.png">

  If student already present in database, then all field filled with that student information and update the necessary fields
  
  <img src="./images/Roll_No_12_Updating.png">
  
* **Updation of student details**
  In order to update student details click on Update button and page will be automatically empty
  
  <img src="./images/Roll_No_12_Update.png">
  
  
 * **If input data is not valid**
 
  It will check if any field is empty then it will pop-up a message that this field is missing and focus goes on to that field
   <img src="./images/Class_Name_Missing.png">

  For invalid enrollment date 

   <img src="./images/Invalid_Enrollment_Date.png">

    
  
  # Installation
  
  Make a folder in your system and clone the project using git bash then open the project in Visual Studio Code or any IDE you prefer.
  ##### Clone the project 
  ```
  git clone https://github.com/ChetanChaudhary6/Student-Enrollment-Form.git
  ```
  After cloning 
  
  Move to **public_html** and then **script** folder and in **script.js** file replace the **connectionToken** by with your Connection Token
  Then come to **index.html** and run this file in the terminal using **start index.html**
  # Sources
  * Introduction to JsonPowerDB - V2.0 course  on  https://careers.login2explore.com/
  * [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/) 
  
