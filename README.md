# techknowthon2.0
hackathon project


**Price Negotiating Chatbot for E-commerce**

Overview
This project is an E-commerce web application that integrates a Price Negotiating Chatbot with both Text and Voice interaction capabilities. Users can browse a list of products and negotiate prices with the chatbot, which offers discounts based on predefined rules.

Features
User Authentication: Signup and Login functionality.
Product Listing: Displays products with actual prices and negotiable prices.
Text-Based Chatbot: Users can enter commands (first price, final price) to negotiate.
Voice-Based Chatbot: Users can negotiate using voice commands via microphone input.
Order Management: Users can place and view orders.
Review & Sentiment Analysis: Users can submit reviews, and the system analyzes sentiment.

Negotiation Logic
"First Price": The chatbot offers a reasonable discount.
"Final Price": If the user requests a final price, an additional 10% discount is applied.
Invalid Commands: Any other input results in an error response.

Usage Instructions
Sign Up → Register an account.
Log In → Access product listings.
Browse Products → View available items.

Negotiate Price
Click on "Text Chatbot Negotiate" to chat via text.
Click on "Voice-Based Chatbot" to negotiate using voice.
Place an Order → Click "Purchase Product" to confirm.
View Orders → Track previous purchases.
Submit & View Reviews → Analyze sentiment of user feedback.

Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: Python (Flask)
Database: SQLite
Speech Recognition: Python SpeechRecognition Library

Future Enhancements
AI-driven negotiation strategies
Multi-language support
Integration with external payment gateways
