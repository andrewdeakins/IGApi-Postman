# IGApi-Postman
Postman Collection for the IG Forex API
Simple collection for postman, 

## Getting Started

1. import the IG Demo Environment and set the variables for API key, api username and api password
2. import the postman collection and your good to go (hit the login request first)

Note: you can open the console to get a status of whats happening.

## Description

I found some of the IG API not to be particularly well designed and inconsistant (a swagger endpoint would have been really useful !) that said, this should help you in getting out the data you need.  IG has endpoints with different versions, you will notice this in the headers where I have supplied a version number.  I have also tried to supply descriptions about the request and the parameters where possible.

## Auth Issues

If you are struggling on the auth side, you may have created a different un/pw combination for the api as this reply to an article suggested suggested:


"Thanks for the replies guys, It turns out I had to create different username and password as edada suggested, although I can't remember reading this anywhere in the documentation but then again I could have easily missed that info.

But in case someone comes cross this issue , you just have to go to classic platform under demo account ( important to do this under demo platform otherwise you won't see this option) and set demo username and password where you set your demo API keys."

## Disclaimer
Im giving this with no warranty whatsoever, Im not responsible for IG locking you out if you hammer their servers or if you wind up placing trades that were not intended.  Thanks for understanding.