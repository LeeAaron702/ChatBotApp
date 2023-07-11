# ChatBot App
![Chatbot](https://github.com/LeeAaron702/ChatBotApp/assets/112150883/dc991895-8d00-487a-9e33-9d239430149b)

This project is a chat application that leverages advanced AI functionalities to improve user experience. Users can send messages, attach files, and receive AI-assisted responses.

## Features
- Login and Registration: Users can register a new account and log in to access the chat application.
- Multiple Chat Types: Users can interact in different types of chat rooms including standard chat, AI-assisted chat, AI text chat, and AI code chat.
- Message Attachments: Users can attach images to their messages.
- AI Assistance: The AI-assisted chat provides automated text suggestions as users type their messages. It also offers code generation in a specific chat room.

------

## Technologies
The main technologies used in this project are:

- React: A JavaScript library for building user interfaces.
- Vite: A build tool that significantly improves development experience.
- Redux Toolkit: The official, opinionated, batteries-included toolset for efficient Redux development.
- React Chat Engine: A set of React components and an API to create a chat interface.
- React Router DOM: Declarative routing for React.
- React Dropzone: A simple HTML5 drag-and-drop zone with React.js.
- Heroicons: A set of beautifully crafted open-source icons.
- Sass: A preprocessor scripting language that is interpreted or compiled into CSS.

## Installation
Before you start, make sure you have Node.js and npm installed on your machine.

Clone the repository

```
git clone https://github.com/your-repo-url/chatgpt-app.git
```

Move into the project directory
```
cd chatgpt-app
```
Install all dependencies
```
npm install
```
To start the client server first cd into client 
```
cd client
```
Start the enviroment
```
npm run dev
```
To start the server cd into server 
```
cd server
```
Start the enviroment
```
npm run dev
```
You can access the main page at:

http://127.0.0.1:5173/


## Usage
- You can use this application by registering a new user or logging in if you already have an account. 

- Depending on the chat room type, you can engage in a normal chat or interact with AI features. 

- You can type your message, attach files, and submit it to send it to the chat. 

### To create an Ai chatroom
- Click the white plus sign to the right of My Chats and input 
```
AiChat
```
- On the right side of the screen click members to activate the accordian and then click 'add member' 

    - select/click AI_bot

- Begin typing messages to GPT 3.5

### To create an Ai Coding chatroom
- Click the white plus sign to the right of My Chats and input 
```
AiCode
```
- On the right side of the screen click members to activate the accordian and then click 'add member' 

    - select/click AI_bot

- Begin typing coding requests to GPT 3.5

### Ai Message Assistance 
- Click the white plus sign to the right of My Chats and input 
```
AiAssist
```
- On the right side of the screen click members to activate the accordian and then click 'add member' 

    - select/click AI_bot

- Begin typing a message, after a space and 1 second chat gpt will autofill the rest of your message.



## Contributing

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## API References

This project uses the following APIs:

- [React Chat Engine API](https://docs.chatengine.io/)
- [OpenAI GPT-3 API](https://beta.openai.com/docs/)

## Contact

Lee Seaver - lee.seaver@gmail.com

GitHub: https://github.com/LeeAaron702


## License
This project is licensed under the ISC (Internet Systems Consortium) license.

The ISC license is a permissive free software license published by the Internet Systems Consortium (ISC). It is functionally equivalent to the simplified BSD and MIT licenses, but without language deemed unnecessary following the Berne Convention.

The ISC license allows permission to use, copy, modify, and/or distribute software for any purpose with or without fee, provided that the license notice and copyright notice is included in all copies.

