Fish Market Chatbot: A Negotiation-Driven Customer Experience

1. Introduction

This project report details the development of a chatbot designed for a fish market, aiming to provide a dynamic and engaging customer experience. The chatbot leverages advanced features like price negotiation, personalized recommendations, and sentiment analysis to offer a unique and user-friendly shopping experience.

2. Project Objectives

Enhance customer engagement: Develop a chatbot that actively engages customers in the purchasing process, fostering a more personal interaction.

Streamline negotiations: Implement a negotiation system that allows customers to adjust factors like quantity, delivery time, and payment terms to influence price.

Provide personalized recommendations: Utilize the customer's feedback and purchase preferences to suggest relevant products and deals.

Improve customer satisfaction: Enhance the overall shopping experience through a user-friendly interface, personalized recommendations, and positive customer interaction.

3. Project Design and Implementation

3.1 Technical Stack:

Python: The core language for chatbot development.

Google Generative AI (GenAI): Provides a powerful AI model for natural language processing and content generation.

Google Cloud Natural Language API: Enables sentiment analysis to understand customer feedback.

Google Cloud Platform (GCP): For hosting and deployment of the chatbot.

3.2 System Architecture:

User Interface: A simple text-based interface, allowing for easy user interaction.

Chatbot Logic: Implemented as a Python function that handles user input, product search, price negotiation, and sentiment analysis.

Product Database: A Python dictionary containing product names, descriptions, and prices.

Negotiation Rules: A set of rules defining discounts based on various factors like quantity, delivery time, and payment terms.

Sentiment Analysis: The Google Cloud Natural Language API is used to analyze the sentiment of customer remarks.

Recommendation Engine: (Not implemented in this version, but potential future development).

3.3 Chatbot Features:

Product Selection: The chatbot greets the user and prompts them to select a desired fish from a list of available products.

Price Negotiation:

Users can choose to negotiate the price, and the chatbot guides them through the process.

Users can adjust factors like quantity, delivery time, and payment terms, which directly influence the final price.

The chatbot provides clear and concise explanations for each discount applied.

Sentiment Analysis:

If the user expresses dissatisfaction with the final price, the chatbot prompts for their concerns.

The Natural Language API analyzes the customer's remark for sentiment.

If the sentiment is negative, the chatbot generates a personalized price decrease suggestion using GenAI.

If the sentiment is not negative, the chatbot informs the user that the deal cannot be fulfilled.

4. Evaluation and Testing

Unit Testing: Each module (product database, negotiation logic, sentiment analysis) was tested individually to ensure proper functionality.

Integration Testing: The complete chatbot was tested as a whole to ensure all features work together correctly.

User Acceptance Testing (UAT): (Not conducted in this phase, but necessary for future development).

5. Future Development

Recommendation Engine: Implement an AI-powered recommendation system that suggests products based on user preferences, purchase history, and current market trends.

Visual Interface: Develop a graphical user interface (GUI) for a more engaging and intuitive user experience.

Integrate with Payment Gateway: Allow users to complete their purchase directly within the chatbot.

Implement Conversational Flow: Enhance the chatbot's dialogue with more natural language processing, allowing for more complex conversations and personalized interactions.

6. Conclusion

The Fish Market Chatbot offers a dynamic and interactive shopping experience for customers. The negotiation system provides flexibility and control, while sentiment analysis ensures responsive and personalized interactions. Future enhancements will focus on integrating a recommendation engine, developing a GUI, and incorporating more advanced conversational capabilities.

7. Appendix

Code Snippet: (Attach a code snippet showing the key parts of the chatbot implementation)

User Guide: (Include a short user guide explaining how to use the chatbot)
