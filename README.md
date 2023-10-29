# LinkedIn-Easy-Apply-Automation-Tool
This app applies to jobs on LinkedIn based on the user's preferences, currently under development as it requires an AI-backed question responding feature 

# LinkedIn Easy Apply Automation

## Short Description
A tool designed to automate the LinkedIn Easy Apply process, streamlining job applications based on user-defined criteria and configurations.

## Detailed Description
This automation tool is tailored to help job seekers efficiently apply to multiple job listings on LinkedIn using the Easy Apply feature. By leveraging Selenium for web automation and a user-defined configuration, it navigates through LinkedIn job search pages, filters job listings, and applies on behalf of the user. The tool is also built with extensibility in mind, featuring settings for other platforms such as AngelCO and GlobalLogic.

## Installation Steps
1. Clone the repository.
2. Install the necessary Python libraries: pip install selenium pyautogui yaml

3. Ensure the `chromedriver` (or respective WebDriver) is correctly set up for Selenium.
4. Update the `config.py` file with your LinkedIn credentials and other configurations as needed.

## Usage Instructions
1. Update the `config.yaml` with your desired job search parameters (e.g., locations, keywords, experience levels).
2. Run the `main.py` script.
3. The tool will start the automation process, applying to job listings based on the configurations provided.

## Other Relevant Information
- The tool was inspired by another GitHub project (please provide the specific project or link if you have it).
- For safety reasons, always keep your login credentials secure and avoid sharing the `config.py` file or pushing it to public repositories.

