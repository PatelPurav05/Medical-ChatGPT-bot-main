# Medical Health Assistant Chatbot with GPT-3 Language Model
This chatbot uses RESTful API that utilizes the GPT-3 language model to provide expert medical advice and assistance to users. The chatbot is designed to help users self-diagnose various illnesses and medical conditions and provide expert advice on self-treatment options using home remedies.

# Getting Started With the API
To get started, you'll need to have an OpenAI API key. You can sign up for one on the OpenAI website.

Once you have your API key, create a .env file in the root directory of the project and add your API key as follows: 

``` 
OPENAI_KEY=your_api_key_here 
```

Next, install the dependencies using npm:

```bash
npm install
```

To start the server, run:

```bash
npm index.js
```

The server should now be running on http://localhost:3000.


To initiate a conversation with the chatbot, launch it in a web browser and type in your messages. To make it easier, use the Live Server extension on VS Code, for which you just need to click the Go Live button on the bottom right of the screen to launch the chatbot.

