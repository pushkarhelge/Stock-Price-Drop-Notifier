# Crash Alert: NIFTY 50 Stocks

This is a project that sends email notifications to users when a stock from NIFTY 50 crashes. The project leverages a range of modern technologies, including HTML, CSS, JavaScript, Node.js, Express, and MongoDB.The project is powered by Nodemailer, a versatile email-sending library that makes it easy to keep users informed about market movements in real time. The project is able to deliver a seamless user experience and help users stay informed and up-to-date on critical market changes.

## Features

* Email notification: The project notifies users via email when a stock from the NIFTY 50 crashes.

* Automated web scraping: The project uses Puppeteer, a Node.js library, to automatically scrape the 52-week low stocks from the Groww website.

* Regular updates: The project uses node-cron to periodically check the stock prices and send notifications when a stock crashes.

* Real-time data: The project uses web scraping to extract stock details directly from the website, ensuring that the data is up-to-date and accurate.

* Simple and easy to use: The project is designed to be easy to set up and use, with a simple interface and clear instructions.

* Environment variable support: The project uses the dotenv library to load environment variables, making it easy to configure and deploy.

* Scalable and extensible: The project is built on Node.js and uses Express and Mongoose, making it easy to scale and add new features as needed.

## How to Run
To run this project on your local machine, you need to install Node.js. Use the latest LTS version available in the download section.
Follow the below instructions to run the project on your local machine:

1. Clone this repository. 
2. Navigate to the project directory.
3. Run npm install to install all the dependencies.

4. Create a .env file in the root directory and set the following variables:
    * makefile
    * Copy code
        MONGODB_URI=<your-mongodb-uri>
        GID = "<your-email>"
        GPW = "<your-email-password-generated-after-2-steps-verification>"

5. Run `npm run devStart` to start the server.

6. Go to http://localhost:3000/ in your web browser.

# Future Improvements

* User authentication: Currently, the project sends email notifications to all the users in the database. To make it more secure, you can add user authentication and allow only registered users to receive the notifications.

* Customize email template: You can provide an option for the users to customize the email notification template as per their preference.

* Support for more stocks: Currently, the project scrapes the data of 52-week low stocks from only one website. You can enhance it to scrape data from multiple websites and add more stocks to the notification list.

* Real-time updates: Instead of running the project at a specified interval, you can implement real-time updates. For this, you can use websockets to listen for updates and notify the users immediately.

* Analytics and Insights: You can add analytics to the project to track the performance of stocks, user engagement, and open rates of the email notifications. This will provide insights on which stocks are being watched the most and which emails are getting the most attention

# 

To contribute to the project, you can open a pull request with your changes.
If you have any questions or issues, feel free to reach out to me at pushkarhelge7777@gmail.com. 

## Thank you for taking the time to read!