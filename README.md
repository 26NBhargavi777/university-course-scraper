# University & Course Data Scraping Assignment

## Overview
This project is part of the AI/ML & Web Scraping Data Entry Intern evaluation process.

The objective was to scrape university and course data using Python and organize it into a structured Excel file while maintaining relational integrity between universities and courses.

## Tools Used
- Python
- requests
- BeautifulSoup
- pandas
- openpyxl

## Files Included
- scraper.py → Python script used for automated web scraping
- University_Course_Data.xlsx → Excel file containing two sheets:
  - Universities
  - Courses

## Excel Structure

### Sheet 1: Universities
- university_id
- university_name
- country
- city
- website

### Sheet 2: Courses
- course_id
- university_id (linked to Universities sheet)
- course_name
- level
- discipline
- duration
- fees
- eligibility

## Key Features
- Fully automated scraping (no manual copy-paste)
- Unique IDs generated
- Proper relational linking between sheets
- Clean and structured dataset
