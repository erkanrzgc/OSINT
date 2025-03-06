# OSINT Username Search Application

## About the Project
This Python application is a GUI-based OSINT (Open Source Intelligence) tool that allows users to search for usernames across various online platforms, including social media, forums, and video platforms.

## Features
- **Username Search:** Enter a username or multiple usernames (comma-separated) to check their existence on different platforms.
- **Category Selection:** Filter search results by platform categories (All, Social Media, Forums, Video Platforms).
- **Progress Bar:** Displays real-time progress during the search process.
- **Result Display:** Shows the search results in a formatted text area with clickable links.
- **Save Results:** Allows users to save search results as a text file.

## Technologies Used
- **Python 3**
- **PyQt5** (For GUI)
- **Asyncio & Aiohttp** (For asynchronous web requests)
- **SSL Handling** (For secure API requests)

## Installation
### Prerequisites
Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

### Install Dependencies
Run the following command to install the required dependencies:
```sh
pip install PyQt5 aiohttp
```

## Usage
1. Run the application:
   ```sh
   python osint_app.py
   ```
2. Enter the username(s) in the input field.
3. Select a category (or choose 'All').
4. Click the 'Search' button to begin the search.
5. View results in the text area.
6. Optionally, save results to a text file.

## Screenshot
![Application UI](screenshot.png)

## Contribution
Feel free to fork this repository and submit pull requests for improvements or additional features.

## License
This project is open-source and available under the MIT License.

## Contact
For any inquiries or issues, please open an issue on GitHub.

