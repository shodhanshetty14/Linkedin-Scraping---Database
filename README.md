# Linkedin-Scraping
Linkedin Website Scraping for Jobs Using Python Selenium And Storing it in the Database Using MySQL-Connector
We have Used Pyautogui to Stoping the program while the User Enter the Captcha To prove he is human

# Working
We Retrieve All the Job Titles/Roles From Careerguid.com.
Then We Redirect to the Linkedin Login Page Were The Bot Enters the provided Credentials.
Then we Search for The Job Roles We Obtained From The Career Guide and Store All the Jobs With Their Application Link and Company Linkedin Page.
We Later redirect to The company's Linkedin page Through The link Stored in the List Then We Receive the Company Description, Number of Employees and Headquarters From their Page.
All these Data are Stored in the Data Structures in the program So we are now Pushing all the data into the Database.
For the Database i have Used XAMPP which has a PHPMYADMIN pannel for Checking the data it is very user friendly and Easy to use.
These Data Are stored in the local Server of my computer.
