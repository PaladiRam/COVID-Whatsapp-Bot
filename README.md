COVID BASED WHATSAPP BOT
This is covid based whatsapp bot and will gives statistics of active,recovered cases for India USA and world.Necessary precautions ,guidelines to be followed are also included as feature in this bot. 

API for live information about COVID-19

GET https://coronavirus-19-api.herokuapp.com/all -> global info

GET https://coronavirus-19-api.herokuapp.com/countries -> all countries info

GET https://coronavirus-19-api.herokuapp.com/countries/{countryName} -> country specific information

Steps followed would be
1. Configure Twilio Whatsapp sandbox using your whatsapp number
2.Created a python virtual environment-
Webhook-The Twilio API for WhatsApp uses a webhook to notify an application when there is an incoming message. The chatbot application needs to define an endpoint that is going to be configured as this webhook so that Twilio can communicate with it.
3.Messages and responses 
The twilio requires an XML bases response from the webhook .Hence the twilio helper library come with classes that help us to create the required responses without XML directly
4.Design chatbot Logic
Using keywords I would include necessary functionality under each keyword and would search for the keyword in the user message.
Based on which the chatbot would respond. here keywords refer to A,B,C,D,E,F
5. Deploy the bot in heroku using procfile where it tells heroku where our app starts
