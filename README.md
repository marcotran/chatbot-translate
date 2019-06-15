# chatbot-translate
# Language translation chat bot
Asisstant is a translation chat bot made with [Microsoft Bot Framework](https://dev.botframework.com/) with [Node.js](http://nodejs.org) and a free [Google translate Api](https://github.com/matheuss/google-translate-api). 




### How it works:
In the beginning, the bot asks you for your source and target language and then it translates whatever you type into it. 



### To run:

> Install dependencies:
```js
npm install
```

> Insert your `appId` and `appPassword`
After installing the dependcies, [create a bot](https://dev.botframework.com/bots/new) on the Microsoft Bot framework. Get the `appId` and the `appPassword`. Replace these values here:

```js

var keys = require('./keys.js'); //Remove it, used only to import appId and appPassword

// Create chat connector for communicating with the Bot Framework Service
var connector = new builder.ChatConnector({
    appId: keys.appId, //Replace with App Id from your Microsoft bot
    appPassword: keys.appPassword //Replace with App Password from your Microsoft bot
});

```
Or create a file named: `keys.js` and export these values. 

> Run the app
```js
node app.js
```


> Install Microsoft Bot Emulator 

Download and Install [Microsoft Bot Framework Emulator](https://github.com/Microsoft/BotFramework-Emulator/releases) to run on localhost.

Enter your appId and appPassword and click connect.









### License
