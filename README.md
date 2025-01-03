# HTMLTableToExcel

Pull Request Exporter from Jira to Excel
This project addresses the need to generate a list of pull requests made on the Jira platform, as it does not provide a native option to export tables to an Excel file.

# Description
A solution was implemented that leverages the platform's capabilities to perform a request that returns data in JSON format. This data was processed and displayed in an HTML file. Additionally, a function was developed to export all the information obtained from Jira to an Excel file, providing an efficient and tailored solution for this use case.

# Features
• Retrieve data from Jira through a request that returns a JSON.
• Process and display the data in a web environment (HTML).
• Directly export the processed information to an Excel file.
• Practical and adaptable solution for similar needs.

# Usage
• Perform the initial configuration to fetch JSON data from Jira.
• View the processed data in the HTML environment.
• Use the export function to generate an Excel file with the required information.

# Requirements
• Access to the Jira API to make requests and fetch JSON data.
• Store the JSON data in an array.
• A compatible browser to view the HTML table.
• View the project on a server (for this development, the "Live Server" extension from Visual Studio Code was used).
• Necessary dependencies for exporting data to Excel (these may vary depending on the implementation).

# Additional Notes
This project was designed as a specific solution to export data from Jira, but it can be adapted to other cases where processing and exporting information from a JSON source is required.
