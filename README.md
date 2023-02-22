# WhatsApp-OpenAi-GPT
This repo is about a quick demo on how to integrate OpenAi GPT models into WhatsApp.
To do so, you need to follow these steps in order:

1 - Create an OpenAi account 
2 - Generate an APIKEY
3 - Create .env file in the project directory and place it there as the following : OPENAI_API_KEY = "<place it here>"
4 - run <npm install> to get the project dependencies installed
5 - run npm start
6 - Link the device by scanning the Qr code from the output console 
7 - Start messaging

The integrated model will respond on behalf of you only if the incoming messsage starts with the prefix 'To bot:'.
This condition can be further refined or altered.
