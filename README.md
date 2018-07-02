Mulesoft project, API and Web Services developed in order to preform operations on a string. 
# String-Functions-API

# Name
stringFunctions

## Author
Tucker Mogren

## Task to Solve
The task for this project was to create three different types of services.

A) The first service was to perform string compression.
A string would be passed into the service and a compressed version of the string is returned.
If the input string is aaabbbbxxxx the output string would be a3b4x4.
If the input string is still smaller then the output string after compression takes place then an error is displayed and the original string is displayed.

B) The second service will tell if a string is unique or not.
Will return the boolean value true or false depending on the string inputted.
The string will be taken via URI parameteres, processed, and a value will be outputted.

C) The third service prepares a string to be taken in a URI, called URIReady.
This service will replace any spaces in the string with a "%20".

## Software
Mule 3.9.0 EE

## Set-Up
Service will be deployed via cloudhub and the URL Endpoints are needed for use. They will be provided in this readme when they are available. (As of 7/2/18 they are not available)
