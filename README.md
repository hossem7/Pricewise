# pricewise

E-Commerce price tracker that applies concepts of data scraping, cron jobs, sending emails and deployment
![image](https://github.com/user-attachments/assets/23507b8b-461f-4802-8c1b-40c203693e47)


Installation

Install the project dependencies using npm:

**npm install**


Set Up Environment Variables

Create a new file named .env in the root of your project and add the following content:
***
#SCRAPER

BRIGHT_DATA_USERNAME=

BRIGHT_DATA_PASSWORD=

#DB
MONGODB_URI=

#OUTLOOK
EMAIL_USER=

EMAIL_PASS=

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on these specific websites from BrightData, MongoDB, and Node Mailer
***
Running the Project
***
**npm run dev**
***
Open http://localhost:3000 in your browser to view the project.
