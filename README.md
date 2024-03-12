
## Overview
Inbox Insights is a Google Apps Script project designed to extract email metadata from Gmail threads and organize it in a Google Spreadsheet for analysis. This tool provides valuable insights into communication patterns, trends, and relationships within your Gmail inbox.

## Features
- **Email Metadata Extraction**: Extracts sender, recipient, date, subject, and body snippet from Gmail threads.
- **Internal Email Detection**: Identifies internal emails based on sender domain.
- **Label Integration**: Retrieves labels associated with Gmail threads for enhanced organization.
- **Google Spreadsheet Integration**: Stores extracted email data in a Google Spreadsheet for easy analysis and management.
- **Customizable**: Easily customizable to suit specific requirements and preferences.

## Usage
1. **Setup Google Apps Script Project**:
   - Open Google Apps Script (script.google.com) and create a new project.
   - Copy the provided script code into the script editor.
   - Save the project and provide necessary permissions.

2. **Configure Parameters**:
   - Modify the `yourDomain` variable in the script to match your organization's domain.
   - Adjust any other parameters as needed to customize the script behavior.

3. **Run the Script**:
   - Execute the `extractEmailsAndSend()` function to start the email extraction process.
   - Check the Google Apps Script logs for any errors or successful completion messages.

4. **Access Extracted Data**:
   - Open the specified Google Spreadsheet to access the extracted email metadata.
   - Analyze the data using built-in Google Sheets features or export it to other tools for further analysis.
