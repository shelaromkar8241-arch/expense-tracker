# Personal Expense Tracker

## Overview
A lightweight Python command-line utility application to help users record daily expenses and generate reports. The tool securely stores date-wise expense entries in a local JSON file, demonstrating practical file I/O operations and date handling.

## Features
* **Add Expense**: Record new expenses with an automated timestamp, category, amount, and description.
* **Automated Date Tracking**: Utilizes Python's `datetime` module to stamp entries.
* **Generate Reports**: Displays a formatted table of all recorded expenses along with a total sum calculation.
* **Data Persistence**: Information is stored locally in `expenses.json`.

## Technologies Used
* Python 3
* JSON module for File I/O
* Datetime module

## How to Run
1. Ensure Python is installed on your system.
2. Open a terminal and navigate to the project directory.
3. Run the script using the following command:
   ```bash
   python main.py
