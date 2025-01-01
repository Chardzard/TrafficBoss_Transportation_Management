## Project Overview
This project aims to design and implement a comprehensive system to manage and optimize urban transportation, focusing on sustainability, efficiency, and user experience.

### Key Features:
- Real-time Traffic Monitoring/Updates
- Public Transportation Management
- Up-to-date landmarks with built-in search functionality
- User Interface with Data Analytics
- Utilizes free TomTom API and map-based SDKs for web

## How to Run the Project
First, run the 'TB_login' SQL script inside your MySQL Workbench instance, then go into the 'app.py' file and add your corresponding SQL user and password
(can also edit 'vars.env' file to include MySQL password if you'd like for better security). The final step is to add your own free TomTom API key to the
'var apiKey' variable on the first line inside the very first <script> tags of the index.html file. From there you can run the application on your localhost,
where it can be accessed over port 5000
