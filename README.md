![Heritage Logo](/images/banner.png)

# Heritage

![Static Badge](https://img.shields.io/badge/Heritage-blue)


Heritage restores endangered indigenous languages and enhances cultural experiences 
through the use of AI.

- ✨ Cultural Restoration ✨
- ✨ language Preservation ✨
- ✨ AI Chatbot ✨

## Prerequisites

Heritage requires:

 1. [Node.js](https://nodejs.org/) v18+ to run.<br>
 2. Gemini API(Google). Get Gemini API from Google AI studio: https://aistudio.google.com/app/prompts/new_chat<br>
3. Clone the Repo:
   
```sh
  git clone https://github.com/irisvlack/heritage.git 
 ```

## Installation
Install the dependencies and devDependencies and start the server on PORT 5501.

```sh
cd heritage
cd specificbot
npm install @google/generative-ai express
node server.js
```
NB: Start server on PORT 5501. In the case PORT number is changed, change PORT number on Server.js too to the PORT number you have changed to.<br>
Also, in kalenjin.html, kikuyu.html, somali.html and luo.html: change the anchor talk localhost port number to the port number you have changed to. The initial anchort tag code is: 

```sh

<a href="http://localhost:5501/" <br>

```

The whole code for the anchor tag is: 

![Anchor tag code](/images/code.png)

## Running Heritage

```sh
cd heritage
start index.html
```
![Heritage Logo](/images/heritage.png)
