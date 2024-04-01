# SAST Scanning Project 

This project aims to demonstrate the importance of Static Application Security Testing (SAST) by utilizing a SAST scanning tool to identify security vulnerabilities in example Python code. 

**What is SAST Scanning**

Static Application Security Testing (SAST) is a method of analyzing source code to identify security vulnerabilities early in the development lifecycle. Unlike dynamic testing, which involves running the application to identify vulnerabilities, SAST analyzes the source code or binary without executing it. This allows SAST to uncover potential security flaws, such as SQL injection, Cross-Site Scripting (XSS), insecure deserialization, and more, before the application is deployed.

In this project, we provide an example Python code snippet containing common security vulnerabilities. These vulnerabilities include:

_SQL Injection_ : Improperly constructed SQL queries that allow attackers to manipulate database queries.

_Cross-Site Scripting (XSS)_: Failure to properly sanitize user input, allowing attackers to inject malicious scripts into web pages viewed by other users.

_Insecure Deserialization_: Deserializing untrusted data without proper validation, leading to potential code execution vulnerabilities.


