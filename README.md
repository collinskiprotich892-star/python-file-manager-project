# Python File Management & Student Report Utility

## Overview

This project consists of two Python automation tools:

### 1️ file_manager.py

A complete file-handling utility that automates:

-   Folder creation\
-   File writing\
-   Reading & displaying data\
-   Backup creation\
-   Archiving\
-   Logging\
-   Optional file deletion

### 2️ students_report.py

A data-processing script that handles:

-   Reading JSON student data\
-   Calculating average scores\
-   Sorting records\
-   Exporting results to CSV

Both scripts demonstrate practical use of Python modules such as **os,
sys, shutil, datetime, json, csv**.

## Purpose

The project was designed to:

✔ Teach practical Python file management\
✔ Demonstrate safe and efficient file operations\
✔ Introduce JSON and CSV processing\
✔ Show real-world automation workflows\
✔ Provide reusable utility scripts

## Project Structure

    python-file-manager-project/
    │── file_manager.py
    │── students_report.py
    │── students.json
    │── README.md

## How to Run

### 1. Clone the repository

    git clone https://github.com/your-username/python-file-manager-project.git
    cd python-file-manager-project

### Run file_manager.py

    python file_manager.py

### Run students_report.py

    python students_report.py

## Sample students.json

    [
      {"id": "S001", "name": "Alice", "scores": [80, 90, 70]},
      {"id": "S002", "name": "Bob", "scores": [60, 75]}
    ]


