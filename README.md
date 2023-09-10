# Site Connectivity Checker

![Site Connectivity Checker](https://img.shields.io/badge/Python-3.6%20%7C%203.7%20%7C%203.8%20%7C%203.9%20%7C%203.10-blue)

This Python project, called "Site Connectivity Checker," is a simple tool that uses the `urllib` and `tkinter` modules to test the connectivity of a website. It provides a graphical user interface (GUI) that allows users to input a web address and checks whether the website is available by examining its HTTP status code.

## How It Works
1. **User Interface**: The project employs the `tkinter` module to create a user-friendly GUI. Users can enter a web address in the provided input field.

2. **Checking Connectivity**: When the user clicks the "Check" button, the program extracts the URL from the input field and uses the `urllib.request` module to open a connection to the specified website.

3. **HTTP Status Code**: The program then retrieves the HTTP status code of the website using the `getcode()` function. A status code of 200 indicates that the website is available, while other status codes signify that the website is unavailable for various reasons.

4. **Displaying Results**: Based on the HTTP status code, the program displays a message to the user, either confirming that the website is available or notifying them that it is not accessible.

## Usage
1. Clone or download the source code for this project.

2. Ensure you have Python installed on your system.

3. Open a terminal or command prompt and navigate to the directory where the project files are located.

4. Run the following command to execute the program:
```bash
python app.py
```
5. The GUI window will appear, allowing you to enter a website URL (e.g., http://www.example.com).

6. Click the "Check" button to test the website's connectivity.

## Additional Notes
You can expand upon this project by customizing the handling of different HTTP response codes to provide more detailed information about the website's status. Feel free to modify and enhance the code to suit your specific needs.

**Enjoy using the `"Site Connectivity Checker"` to quickly verify website availability!**