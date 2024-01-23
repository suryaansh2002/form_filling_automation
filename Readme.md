# Form Filling Automation

Selenium Script Developed for the Department of Computer Science, MIT Manipal.

The script was developed to simplify the manual work being done by the faculty of filling the Mentor form sheet.

**Project Website:** [https://mitcse.manipal.edu/](https://mitcse.manipal.edu/)

## Overview

This project provides an automation solution for filling out the Mentor form sheet. It is aimed at reducing the manual work required by the faculty.

## Getting Started

To run this automation on your local machine, follow the steps below:

### Clone the Repository

```bash
git clone https://github.com/suryaansh2002/form_filling_automation.git
```
### Usage

- If running as a student:

  ```bash
  python3 test.py
    ```
- If running as a faculty:

  ```bash
  python3 main.py
    ```    
## Files and Directories

- Extracurricular.pdf and Mentor Details.pdf: Blank PDF files to be downloaded as templates.

- SLCM Automation.ipynb: Jupyter notebook file of the code.

- main.py: Python Selenium web scraping script handling faculty login.

- test.py: Python Selenium web scraping script handling student login.

- chromedriver.exe: Chromedriver for Google Chrome Browser (version 107). You can replace it with the Google Chrome driver for your browser version by downloading it.

- template.xlsx and student_details_template.xlsx: Template Excel files used to take in data and format as output PDF.


