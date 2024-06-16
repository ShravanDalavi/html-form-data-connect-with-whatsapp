# Html form data connect with whatsapp
![image](https://github.com/ShravanDalavi/html-form-data-connect-with-whatsapp/assets/172488772/3dddd286-ad12-43b0-ad00-28c2c717767e)

A Pen created on CodePen.io. Original URL: [https://codepen.io/Shravan-Dalavi/pen/vYwWExv](https://codepen.io/Shravan-Dalavi/pen/vYwWExv).
# Introduction
WhatsApp Web is a web-based extension of the popular WhatsApp messaging application. It allows users to access their WhatsApp conversations and send/receive messages directly from their web browsers. Integrating HTML forms with WhatsApp Web can enhance user experience and streamline communication.
# System Architecture
The system comprises three main components:
1.	HTML Form: A simple form collecting user data.
2.	JavaScript: Handles form submission and sends data to WhatsApp.
3.	CSS: Styles the form for a user-friendly interface.
# Features
## User Interface ##
•	Responsive Design: The form is styled to be visually appealing and user-friendly.
•	Form Fields: Includes fields for Name, Email, and Message.
•	Submission Button: A button to submit the form data.
## Functionality ##
•	Data Collection: Collects user input from the form fields.
•	WhatsApp Integration: Uses the WhatsApp API to send data as a message.
•	Dynamic Message Creation: Constructs a message string with the form data.
# Implementation Diagrams
1.	Create an HTML Form: Design a form with fields for the user to fill out. This form will collect the data that you want to send to WhatsApp.
2.	Write a JavaScript Function: Develop a JavaScript function that will be triggered when the form is submitted. This function will handle the data from the form and format it into a message.
3.	Integrate WhatsApp API: Use the WhatsApp API to send the formatted message. You’ll need to set up an account with WhatsApp Business API and get access credentials.
4.	Open WhatsApp Chat: The API will use the message data to open a chat window in the user’s WhatsApp application, allowing them to send the message.
# System Architecture Diagram
![whatsapp system](https://github.com/ShravanDalavi/html-form-data-connect-with-whatsapp/assets/172488772/a07b3df9-dd32-49e5-96cd-57bd33151809)
# Data Flow Diagram
![whatsapp Data Flow](https://github.com/ShravanDalavi/html-form-data-connect-with-whatsapp/assets/172488772/82076f33-f42f-45b3-bb59-b839dd54333a)
# Integration with WhatsApp
## How it Works ##
1.	User Input: The user fills out the form with their name, email, and message.
2.	Form Submission: Upon clicking the submit button, the send To WhatsApp function is invoked.
3.	Message Construction: The function constructs a URL with the form data.
4.	WhatsApp API: The URL is opened in a new tab, redirecting to WhatsApp Web with a pre-filled message.
## Advantages ##
•	Direct Communication: Allows for immediate interaction with users via WhatsApp.
•	Ease of Use: Users can send messages without needing to manually enter details.
# Conclusion
Integrating HTML form data with WhatsApp Web streamlines communication and enhances user engagement. The implementation is straightforward, involving basic HTML, CSS, and JavaScript. This integration provides a seamless way to connect with users and receive their inquiries or feedback directly through WhatsApp.
# References
1.	MDN Web Docs: HTML, CSS, JavaScript
2.	How can I send HTML enquiry form data to multiple WhatsApp contacts
