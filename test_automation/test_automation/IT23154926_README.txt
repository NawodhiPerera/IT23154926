Chat Translator Test Automation
Student ID: IT23154926

Module: ITPM - Assignment 01

1. Description
This project implements an automated testing framework for the "Chat Translator" web application. The tool automates the process of entering Singlish text, triggering transliteration, and capturing the resulting Sinhala Unicode output.

2. Setup Instructions
To set up the environment, run the following commands in your terminal:

DOS
pip install playwright pandas openpyxl
playwright install chromium

3. Project Structure
test_automation.py: The core Python script using Playwright for browser automation.

Assignment 1 - Test cases.xlsx: The Excel workbook containing 50 test cases, expected outputs, and the automated results.

README.pdf: Project documentation.

4. How to Run
To execute the test suite, navigate to the project folder and run:

DOS
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --sheet " Test cases" --wait-ms 15000 --type-delay-ms 150 --save-every 1

5. Test Coverage
The test suite includes 50 cases covering:

Question & Command forms

Greetings & Requests

Romanization Variants (e.g., shorthand)

Mixed English/Singlish phrases

Digital terms, Emojis, and Punctuation
