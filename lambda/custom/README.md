# Alexa Template - HTTP using request-promise

This template that shows how to use the request-promise module in an Alexa skill.
This template uses the [Alexa Skills Kit for Node.js](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs) version 2.0 and is designed to be used with the [Alexa Skills Kit CLI](https://developer.amazon.com/docs/smapi/ask-cli-intro.html).

This Lambda function in Node.js implements a basic handler of each of the required Intents, and adds one hander, for RequestIntent, which is defined in the interaction model.

The RequestIntentHandler.handle function returns a Promise, which is resolved by calling out to an HTTP service.
