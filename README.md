# HTTP-Honeypot
A Flask-based HTTP honeypot with a fake login page that logs IPs, usernames, and passwords. Uses rotating logs and customizable credentials. For educational use only.

A lightweight web-based honeypot built using Flask. It simulates a login page to log unauthorized access attempts including usernames, passwords, and IP addresses. Ideal for educational and research purposes in cybersecurity.

Features
Fake login page (webpage.html)

Logs:

IP address

Username and password attempts

Rotating log files (web_records.log) to manage log size

Configurable credentials (default: admin / password)

Easy to run and extend

Requirements
Python 3.x

Flask (pip install flask)
