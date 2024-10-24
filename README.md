Automated Report Download and File Management for BI Portal
Overview
This project automates the process of downloading reports from the BI Portal, checking the file downloads, renaming them based on specific rules, moving them to a shared drive, and notifying a Slack channel when the process is completed. The script uses Selenium for browser automation, PyAutoGUI for controlling certain interface elements, and other Python libraries for file and date management.

Features:
Automates login and report generation on the BI Portal.
Downloads reports in Excel and CSV format.
Renames and moves files to the correct folder based on predefined rules.
Validates file downloads to ensure completion before processing.
Sends notifications to a specified Slack channel when the operation is complete.
Handles multiple report types with specific filters.
Requirements
Python 3.x
Chrome WebDriver
Selenium
PyAutoGUI
pywin32 (for handling system keys like Caps Lock)
Requests (for sending HTTP POST requests)
