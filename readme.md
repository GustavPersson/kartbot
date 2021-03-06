# kartbot

> Slack bot for Mario Kart and Fifa tournaments

Play games with colleagues at work? Use Slack? Use this bot to challenge random colleagues to a bunch of games! (provide your own games)

## Install

```
$ npm install --save kartbot
```

## Usage

```js
const kartbot = require('kartbot');

kartbot({
  token: YOUR_TOKEN_HERE, // Add a bot at https://my.slack.com/services/new/bot and copy the token here.
  autoReconnect: true, // Automatically reconnect after an error response from Slack.
  autoMark: true // Automatically mark each message as read after it is processed.
});
```

## Commands
`!kart` - Challenge random channel members to Mario Kart

`!fifa` - Challenge random channel members to a game of Fifa

`!smash` - Challenge random channel members to Smash Bros

`!nokart` - Reject a challenge

`!list` - See who's currently challenged

`!roll USER` - Challenge someone in the channel to a game of chance

## License

MIT © [Paul Asjes](http://internetjones.net)
