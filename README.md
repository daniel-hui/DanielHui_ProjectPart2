# DanielHui_ProjectPart2

Daniel Hui    
Project Part2   
CS1520    
4/28/17   

There were several main changes, most of which were related to PHP. Firstly, there was learning and becoming familiar with the overhead required to correctly display and use .php files opposed to .html files. A portion of this overhead included using XAMPP in order to host the files, as well as configuring it and making sure it is working correctly. Once XAMPP was functioning correctly, I was able to implement some actual PHP features. One big use of it was to use an 'include' file for the footer, as it displayed the same thing on each page and so using PHP was much more practical and clean, and would have been easier to implement initially.

The largest PHP portion was related to the database. This work included first instantiating the database, connecting to it, configuring it, and finally actually acting on it. In order to do these tasks, PHP commands which called SQL components were utilized. The main functionality of the database was to store the emails of users, via the contact form. The functionality is not complex, but demonstrates implementation of database interactivity. Specifically, what is done is that a user will send an email, which requires them to input their email address, a subject, and a message -- this function is done through an HTML form and a JavaScript function to check the inputs' validity. The email address is then POST'ed, and can be accessed via subsequent PHP code. After the database is constructed and connectivity is established, the email address is INSERT'ed into a table for future querying and other operations. 
