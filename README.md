# Web-Based SQL injection and prevention system

#### This system is designed to demonstrate the importance of preventing SQL injection attacks in web applications. It includes a login form that accepts user input and validates it against a database using PHP and MySQL.

# 💉what is SQL injection?
SQL Injection, is a type of web application security vulnerability that allows an attacker to interfere with the queries that an application makes to its database. It is a code injection technique that attackers can use to exploit vulnerabilities in web applications that use SQL as their database language. and this is  that kind of technique used to retrieve or destroy data from a database without permission. It is considered one of the top web application security risks. Where data fuels the core functionalities of web applications, ensuring the security of databases is of paramount importance. Web-based SQL injection occurs when an attacker manipulates input fields on a web application to inject malicious SQL code, potentially compromising the underlying database. 




##### Suppose your PHP application processes user data based on input to generate SQL queries, and suddenly, an anonymous attacker secretly injects a malicious SQL query in the input field.These are common problems that I have noticed in PHP based web applications


# SQL Injection Prevention in PHP Website

To prevent SQL injection attacks in PHP web applications when processing user input, it's essential to use prepared statements with parameter binding. 
1. Use prepared statements with parameter binding to separate SQL code from user-supplied data.</BR>
2. Never concatenate user input directly into your SQL queries.</BR>
3. Use a database abstraction library that supports prepared statements, such as PDO or MySQLi.</BR>
4. Implement stored procedures in the database to prevent SQL injection attacks.</BR>
5. Always filter and sanitize all inputs used to build SQL queries.</BR>

Note: The example discussed below can be found in the [sql-injection folder](https://github.com/pgreen24/web-based-SQL-injection-and-prevention-system/tree/main/SQL%20injection)

# Installation:

To install this project, follow these steps:

Download and install XAMPP</br>
Install a text editor (Sublime Text, Visual Studio Code, or Atom)</br>
Download the project as a zip file or clone it from GitHub</br>
Move the project to the root directory of your XAMPP installation</br>
Import the database using phpMyAdmin</br>
Make changes to the settings in the config folder</br>
Open the project in your browser and start using it</br>

# 🔐Security:
 take security seriously, and this release includes measures to prevent SQL injection attacks. However, i recommend that you follow best practices for securing your database and server.

### Languages Used

| Language | Version |
|----------|---------|
| PHP      | 7.4     |
| SQL      | 5.7     |

# Create Website for Requirement Application
•	Visual Studio</br>
•	XMAPP</br>

# Create Website for Back End Code Requirement
•	HTML</br>
•	CSS</br>
•	JAVA SCRIPT</br>
•	PHP</br>
•	MY SQL</br>

## Checking Security for Web Application using Burp Suite and SQL Map</br>

## Burp Suite</br>

Burp Suite is a comprehensive toolkit for web application security testing. Here's a step-by-step guide on how to use Burp Suite to check security for a web application:</br>

1.Install and configure Burp Suite: Download and install Burp Suite from the official website. Configure the proxy settings in your browser to point to Burp Suite.</br>
2.Scan the web application: Enter the URL of the web application in Burp Suite and start the scan. Burp Suite will crawl the website and identify potential vulnerabilities.</br>
3.Analyze the scan results: Review the scan results to identify potential vulnerabilities such as SQL injection, cross-site scripting (XSS), and cross-site request forgery (CSRF).</br>
4.Exploit vulnerabilities: Use Burp Suite's exploitation tools to test the identified vulnerabilities and verify their existence.</br>

# SQL Map

SQL Map is an open-source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws. Here's a step-by-step guide on how to use SQL Map to check security for a web application:</br>

1.Install SQL Map: Download and install SQL Map from the official website.</br>
2.Identify potential injection points: Use SQL Map to identify potential injection points in the web application, such as user input fields.</br>
3.Scan for SQL injection: Use SQL Map to scan the identified injection points for SQL injection vulnerabilities.</br>

##### Exploit SQL injection: Use SQL Map to exploit the identified SQL injection vulnerabilities and extract sensitive data.</br>

###More comprehensive information is provided in the accompanying PDF.
