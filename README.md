**In the repository there are a few examples of SOAP and REST Postman test.**

**SOAP requests come from public API's and include:**
- Celsius to Farenheit Conversion
- Changing int numbers to their written equivalents
- Link to country flag based on its ISO code

Example response body and different header types (application/soap+xml, text/xml; charset=utf-8)  are used to specify the expected response

**REST requests are done following the course "Postman API Test Automation for Beginners" by Valentin Despa - https://www.youtube.com/watch?v=zp5Jh2FIpF0&t=4950s&ab_channel=freeCodeCamp.org**

They demontstrate the use of some useful postman practices such as:
- postman variables to avoid redundancy
- JS-like callback Postman functions to make a number of different assertions
- JSON responce body analyses to verify the correct format of returned data
- Fixed expressions to analize the exact content of the response - not just its type
- Checking response status
- Scope of variables - both for postman and JS
- CI/CD integration possibilty while running collection test through Github actions

Having successfully completed this course I have received an API test automation badge from Postman.
