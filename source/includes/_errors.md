# Errors

<aside class="notice">Some APIs have extended error codes or more specific meanings for a given code.</aside>

The Backline API uses the following error codes:

Error Code | Meaning
---------- | -------
400 | Bad Request -- Your request sucks
401 | Unauthorized -- Your API key is wrong
403 | Forbidden -- The API requested is hidden for administrators only
404 | Not Found -- The specified request returned no data
405 | Method Not Allowed -- You tried to access a API with an invalid method
406 | Not Acceptable -- You requested a format that isn't json
500 | Internal Server Error -- We had a problem with our server. Try again later.
503 | Service Unavailable -- We're having a system issue. Please try again later.
