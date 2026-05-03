# test_automation
Assignment 1 - Singlish Transliteration Testing
# Assignment 1 - Singlish Transliteration Testing

## Description
This project tests the Chat Sinhala transliteration function of the 
pixelssuite chat translator application using Playwright automation.

## Prerequisites
- Python 3.11 or higher
- Google Chrome browser

## Installation

Step 1 - Clone the repository
git clone https://github.com/YOURUSERNAME/test_automation.git
cd test_automation

Step 2 - Install dependencies
pip install playwright openpyxl
playwright install

## How to run the tests
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

## Results
Results are automatically saved in the Excel file under 
Actual output and Status columns.
