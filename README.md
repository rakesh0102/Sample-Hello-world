Api.ai - sample webhook implementation in Python
This is a really simple webhook implementation that gets Api.ai classification JSON (i.e. a JSON output of Api.ai /query endpoint) and returns a fulfillment response.

More info about Api.ai webhooks could be found here: Api.ai Webhook

Deploy to:
Deploy to Heroku

What does the service do?
It's a weather information fulfillment service that uses Yahoo! Weather API. The services takes the geo-city parameter from the action, performs geolocation for the city and requests weather information from Yahoo! Weather public API.

The service packs the result in the Api.ai webhook-compatible response JSON and returns it to Api.ai.
