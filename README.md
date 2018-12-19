# CLI-dictionary-app
This is a dictionary app- powered by oxford API.

Takes input from command line and displays dictionary meaning for that word.
 
 
 usage:
    ./dict <command>

    commands: 

    ./dict def:      fetches the meaning of the word entered.
    ./dict syn:      fetches the synonmys for the word entered.
    ./dict ant:      fetches the antonyms for the word entered.
    ./dict ex:       fetches some examples for the word entered.
    ./dict full:     fetches all the above details for the word entered.
    
    ./dict play:     Game displays display a definition, synonym, or antonym. 
                     You have to guess the word.


Dep:

node's built in readline module: for reading input from CLI

axios: for making http requests

chalk: for coloured output in CLI.

Linted using Eslint - Airbnb style guide
