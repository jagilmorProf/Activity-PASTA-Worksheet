# PASTA worksheet
**27th November 2023**

## Overview
You’re part of the growing security team at a company for sneaker enthusiasts and collectors. The business is preparing to launch a mobile app that makes it easy for their customers to buy and sell shoes. 
You are performing a threat model of the application using the PASTA framework. You will go through each of the seven stages of the framework to identify security requirements for the new sneaker company app.

### Sneaker Company Description
Our application should seamlessly connect sellers and shoppers. It should be easy for users to sign-up, log in, and manage their accounts. Data privacy is a big concern for us. We want users to feel confident that we’re being responsible with their information.<br>
Buyers should be able to directly message sellers with questions. They should also have the ability to rate sellers to encourage good service. Sales should be clear and quick to process. Users should have several payment options for a smooth checkout process. Proper payment handling is really important because we want to avoid legal issues.

## Stages	Sneaker company
I. **Define business and security objectives**<br>
   Make 2-3 notes of specific business requirements that will be analyzed.
   - Will the app process transactions?
   - Does it do a lot of back-end processing?
   - Are there industry regulations that need to be considered?
   The business application will process sales and allow for users to manage their accounts. There will be concerns about the processing of payments, ensuring it is done in an appropriate and legal fashion.

II. **Define the technical scope**<br>
    List of technologies used by the application:<br>
    - API<br>
    - PKI<br>
    - AES<br>
    - SHA-256<br>
    - SQL<br>
    With the utilization of SQL, it is advised to evaluate the risks of SQL injection attacks as it is the most prominent vulnerability on the list. The SHA-256 hash function is aimed at protecting user passwords and credit card information. Session hijacking is to be evaluated with the API and PKI technologies.

III. **Decompose application**
    ![Pasta-2.png](https://github.com/jagilmorProf/Activity-PASTA-Worksheet/blob/main/Pasta-2.png)

IV. **Threat analysis**<br>
    List 2 types of threats in the PASTA worksheet that are risks to the information being handled by the application.<br>
    - What are the internal threats?<br>
    - What are the external threats?<br>
    Internal threats identified will be weak login credentials. It is essential that users are subject to adequate self-imposed password security measures, such as 13 character passwords, as well as multi factor authentication.<br>
    External threats will be identified as injection attacks that the SQL database could be exposed to. The development team will need to evaluate this risk to ensure that the SQL vulnerabilities cannot be exposed.<br>

V. **Vulnerability analysis**<br>
    List 2 vulnerabilities in the PASTA worksheet that could be exploited.<br>
    - Lack of prepared statements<br>
    - Weak Login Credentials<br>

VI. **Attack modeling**
    ![Pasta-1.png](https://github.com/jagilmorProf/Activity-PASTA-Worksheet/blob/main/Pasta-1.png)

VII. **Risk analysis and impact**<br>
    List 4 security controls that you’ve learned about that can reduce risk.<br>
    - Utilizing the SHA-256 hashing method<br>
    - Principle of least privilege<br>
    - Incident response procedures<br>
    - Adequate password policies.<br>
