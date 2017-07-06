# Consuming-Public-APIs
##Consuming the Google API for youtube
> The program provided is searching youtube videos using it API
>it needs to pass the the Arguments via commandline and it will return the results and the default
if no arguments provided ,it will search "This is Andela"
>A sample image has been attached  "sampleResults.png"
---
##Consuming the Google API for Google Sheets
>Has dependency on gspread and oauth2client module one would need to pip them.
.Must include client_secret.json file with in the same working directory as the .py file
>Im through an error:```HttpAccessTokenRefreshError: invalid_grant: Invalid JWT: Token must be a short-lived token and in a reasonable timeframe```
>This is caused by  by a poor synchronisation of the [computer's clock  where the code was executed with the server clock](https://stackoverflow.com/questions/30115933/access-token-and-refresh-token-giving-invalid-grant-in-google-plus-in-python/30117441#30117441)
>Else it works fine and will retrieve and output data from my registration.xlsx google sheet
