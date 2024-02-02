# Secure-Online-Store


## Introduction

Welcome to the Secure Online Shop project, a compact educational exercise focusing on identifying and mitigating web application vulnerabilities.

The primary goal is to develop a functional online shop selling memorabilia while discreetly integrating specific vulnerabilities for educational exploration, including Cross-Site Scripting (CWE-79) and SQL Injection (CWE-89).

Aligned with the Application Security Verification Standard (ASVS) Level 1, this project follows a set of security requirements to guide the design, development, and testing of secure web and mobile applications.


## Project Execution and Delivery
### Group Members

This project was implemented by a group of five students:

    Student 1: Vasco Faria      -107323     vascomfaria@ua.pt
    Student 2: Goncalo Lopes    -107572     goncalorcml@ua.pt
    Student 3: Tiago Cruz       -108615     tiagofcruz78@ua.pt
    Student 4: Rodrigo Graça    -107634     rodrigomgraca@ua.pt
    Student 5: Gabriel Couto    -103270     gabrielcouto@ua.pt
    
    



## Project Setup

### Frontend
	* React JS - Employed for the creation of the user interface (UI) to enhance the overall user experience.

### Backend
	* Node JS - Employed for the creation of the backend server, which handles the requests from the frontend and communicates with the database.

### Database
	* SQL - Employed for the creation of the database, which stores all the information related to the online shop.
	



## Vulnerabilities

The following vulnerabilities were identified during the analysis of this project, and were then properly corrected in app_sec:

    CWE-79  : Improper Neutralization of Input DuringWeb Page Generation (’Crosssite Scripting’)

    CWE-89  : Improper Neutralization of Special Elements used in an SQL Command (’SQL Injection’)

    CWE-256 : Plaintext Storage of a Password

    CWE-620 : Unverified Password Change

    CWE-262 : Not Using Password Aging

    CWE-522 : Insufficiently Protected Credentials

    CWE-488 : Exposure of Data Element to Wrong Session

    CWE-521 : Weak Password Requirements

    CWE-20  : Improper Input Validation



### Project Execution
To execute this project you need to open the terminal in 3 different directories.

1. In the first directory (named 'db') you need to execute this command:
    - ```cd db``` (to go to the directory)
    - Then ```docker compose build``` and ```docker compose up```

2. In the second directory (named 'Server') you need to execute the following commands:
    - ```cd Server``` (to go to the directory)
    - ```npm run dev```

3. In the third directory (named 'deti_store') you need to execute the following commands:
    - ```cd deti_store``` (to go to the directory)
    - ```npm start```

> [!NOTE]
> These commands must be executed by this specific order, otherwise the project will not work properly. 




