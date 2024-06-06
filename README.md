# Amazon Lex Chatbot -  BankerBot

## Description

BankerBot leverages Amazon Lex and AWS Lambda to provide a robust and scalable solution for banking inquiries. The chatbot is capable of understanding and processing various user intents, ensuring smooth and effective interactions.

## Features

- **Amazon Lex Integration**: Utilizes Amazon Lex to build the conversational interface.
- **AWS Lambda**: Integrates with AWS Lambda for real-time data processing.
- **Fallback Intents**: Designed to handle unclear user requests efficiently.
- **Custom Slot Types**: Employs custom slot types for precise user input handling.
- **Voice Commands**: Supports voice-based interactions for ease of use.

## Setup Instructions

### WelcomeIntent:
- Define a basic intent
- Create lists of utterances
- Handling failures i.e. FallbackIntent
- Define a MessageGroup to provide a semi-random response
- Build and test your bot using text and speech

### CheckBalance:
- Define a custom slot type
- Associate custom and built-in slots to your intent
- Parse slot values from the initial utterance
  
### Lambda function:
- Set up a Lambda function
- Integrate the Lambda function with your chatbot's alias
- Use code hooks to perform the final fulfilment step of the intent

### Just a few more...
- Use context carryover of certain slot values from one intent to the next
- Set up two different slots that use the same underlying slot type
- Set up a confirmation prompt

## Key Learning
- Amazon Lex: Gained insights into building conversational interfaces with Amazon Lex.
- AWS Lambda: Learned to integrate Lambda functions for dynamic response handling.
- CloudFormation: Utilized CloudFormation for efficient resource management and deployment.
- Chatbot Development: Developed skills in creating user-friendly and responsive chatbots.
  
## Future Enhancements
- Connecting with Application/Databases:Enabling dynamic data retrieval and updates, allowing the chatbot to provide real-time information.
- Enhanced Functionality: Adding more complex banking features such as loan inquiries and investment advice.
- Multilingual Support: Expanding the chatbot to support multiple languages.
- Improved AI Models: Integrating advanced AI models for better understanding and response accuracy.

## Project Details
The project involved creating a comprehensive banking chatbot capable of understanding user queries related to balance inquiries and fund transfers. The chatbot was designed to handle both text and voice inputs, making it accessible and convenient for users. Aprart from this, made the chatbot using AWS CloudFormation which was worth it, ensuring a smooth and scalable setup process
‍
## Final Thoughts
BankerBot represents a significant step forward in the integration of conversational AI with banking services. The use of Amazon Lex and AWS Lambda has enabled the creation of a responsive and intelligent chatbot that can greatly enhance the user experience. This project has been a valuable learning experience and has opened up numerous possibilities for future enhancements and applications.
