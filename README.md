You will need to fetch a bearer token from Twitter as documented Here, once you have it you can use it as follows.

var client = new Twitter({
  consumer_key: '',
  consumer_secret: '',
  bearer_token: ''
});
## Requirements

- node and npm

## How to Use

1. Clone the repo: `
2. Go into folder: `cd react-tweets`
3. Install dependencies: `npm install`
4. Create local MongoDB database called **react-tweets** (configured in `server.js`)
5. Replace credentials for Twitter API (configured in `config.js`)
6. Start the app: `node server.js`
7. View in browser at: `http://localhost:8080`
8. Tweet away!
"# react-tweets-master" 
