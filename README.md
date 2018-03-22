You will need to fetch a bearer token from Twitter as documented https://apps.twitter.com/app/

var client = new Twitter({
  consumer_key: '',
  consumer_secret: '',
  bearer_token: ''
});

## Requirements

- node and npm

## How to Use

_ Clone this repo 
_ Install dependencies: `npm install`
_ Create local MongoDB database called **react-tweets** (configured in `server.js`)
_ Replace credentials for Twitter API (configured in `config.js`)
_ Start the app: `node server.js`
_ View in browser at: `http://localhost:8080`
_ Tweet away!

