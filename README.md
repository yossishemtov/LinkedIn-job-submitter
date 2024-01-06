# LinkedIn Job Application Automation

## Overview

This Python script leverages the Selenium WebDriver to automate the job application process on LinkedIn. It logs into a LinkedIn account, navigates to the job search page, applies filters based on location and keywords, and then automatically applies to job listings.

## Features

- **Automated Job Applications**: The script automates the process of navigating through job listings, clicking on them, and submitting job applications.

- **Account Login**: Requires LinkedIn account credentials for automated login.

- **CAPTCHA Handling**: Includes a manual step to solve CAPTCHA puzzles, allowing the script to continue after user intervention.

## Prerequisites

- **Python**: Make sure you have Python installed. You can download it from [python.org](https://www.python.org/downloads/).

- **Web Browser**: The script uses Chrome by default. Ensure you have [Chrome](https://www.google.com/chrome/) installed. You can modify the script to use other browsers if needed.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/linkedin-job-automation.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Update script variables:
   - Replace `YOUR LOGIN EMAIL`, `YOUR LOGIN PASSWORD`, and `YOUR PHONE NUMBER` with your LinkedIn account credentials.

## Usage

1. Run the script:
   ```bash
   python automate_linkedin_jobs.py
   ```

2. Follow the on-screen instructions, including manually solving the CAPTCHA when prompted.

## Important Notes

- This script is intended for educational purposes only. Use it responsibly and in compliance with LinkedIn's terms of service.

- Be aware of LinkedIn's policies regarding automated activity. Excessive automation may lead to account restrictions.

## Contributing

If you'd like to contribute to the project, feel free to submit a pull request or open an issue.

Feel free to customize this template according to your specific requirements and project details. Provide clear instructions on how users can set up and use your automation script.
