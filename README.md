#CSC361 Assignment 1 - Smart Web Client

The Smart Web Client is a Python script that performs various tasks related to 
a given URL: including checking HTTP/2 support, parsing and printing cookies, and 
checking if the website is password-protected. It also handles HTTP 300-level redirects 
and follows them recursively.

Prerequisites
- Python 3.x
- Required Python libraries: `socket`, `ssl`, `sys`, `re`

Error Handling
The script includes error handling to gracefully handle exceptions that may occur 
during execution. Any errors encountered are printed with informative messages to 
help diagnose and address issues.

Usage
1. Clone or download the repository to your local machine.
2. Open a terminal or command prompt.
3. Navigate to the directory where the script (`website_analysis.py`) is located.
4. Run the script by using the following command:

   python SmartClient.py <url>

For example
- python SmartClient.py www.google.com
- python SmartClient.py netflix.com
- python SmartClient.py https://docs.engr.uvic.ca/docs/
