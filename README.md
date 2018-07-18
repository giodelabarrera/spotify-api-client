
# Spotify API Client

Sorry for my english.
This library should execute on the side-server.

## Get Access Token

Of moment to can use this method open the navigator with the link https://accounts.spotify.com/api/token

In the console paste the code del file spotify-api-client.js and execute:

```js
spotifyApiClient.getAccessToken('<your-client_id>', '<your-client-secret>');
```

And obtains a object with property access_token that we can use in our next request
