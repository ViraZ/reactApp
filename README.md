You will need to fetch a bearer token from Twitter as documented https://apps.twitter.com/app/

var client = new Twitter({
  consumer_key: '',
  consumer_secret: '',
  access_token_key: '',
  access_token_secret: ''
});

## Requirements

- node and npm

## How to Use

1. Clone this repo 
2. Install dependencies: `npm install`
3. Create local MongoDB database called **react-tweets** (configured in `server.js`)
4. Replace credentials for Twitter API (configured in `config.js`)
5. Start the app: `node server.js`
6. View in browser at: `http://localhost:8080`
# Tweet away!

