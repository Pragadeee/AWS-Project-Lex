# AWS-Project-Lex
Amazon Lex Chatbot for Application Integration This project features a conversational chatbot built with Amazon Lex, designed to streamline and automate user interactions within applications. Leveraging natural language understanding (NLU), the chatbot interprets user queries and provides relevant responses.
Key Features
Custom Intents and Slot Types:
CheckBalance and TransferFunds intents allow users to check balances and transfer funds between accounts.
Custom slot type accountType distinguishes between various account types.

Lambda Integration:
AWS Lambda functions handle backend logic, fetching data and executing user requests dynamically.

Context Management:
Context carryover between intents, enabling the chatbot to remember user choices and improve the conversational flow.

Dynamic Responses:
Variations in responses based on user inputs and slot types, creating a natural interaction experience.

Setup and Configuration:
Intents and Slots: Set up intents like WelcomeIntent, CheckBalance, and TransferFunds, complete with confirmation prompts and error handling (FallbackIntent).
Contextual Conversations: Utilize output contexts from CheckBalance to enable follow-up queries without needing redundant information.
Visual Builder: Use Amazon Lex's conversation flow builder to map out user interactions visually.

How to Use
Deploy Lambda Functions: Follow the steps to deploy custom AWS Lambda functions that interact with your Lex bot.
Customize Slot Types: Modify accountType or add new slot types based on user needs.
Test and Adjust: Experiment with conversation flow, slot prompts, and response variations to fine-tune user experience.
Our bot now handles both checking balances and transferring funds between accounts, providing a comprehensive and intuitive banking support experience!
