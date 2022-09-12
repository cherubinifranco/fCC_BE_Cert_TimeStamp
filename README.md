# Timestamp Microservice

This is the first project for the Back End Development and APIs Certification in freeCodeCamp.com


You can find the full assignment here:

https://www.freecodecamp.org/learn/back-end-development-and-apis/back-end-development-and-apis-projects/timestamp-microservice


## "/api" 
    Should return the current date as a JSON Object with a UNIX timestamp and an UTC one.

## "/api/n" being n a UNIX timestamp 
    Should return the date given as a JSON Object with the UNIX timestamp and an UTC one.

## "/api/m" being m a UTC timestamp 
    Should return the date given as a JSON Object with a UNIX timestamp and an UTC one.


## Example
    A request to /api/1451001600000 should return { unix: 1451001600000, utc: "Fri, 25 Dec 2015 00:00:00 GMT" }

    A request to api/2015-12-25 should return { unix: 1451001600000, utc: "Fri, 25 Dec 2015 00:00:00 GMT" }
    