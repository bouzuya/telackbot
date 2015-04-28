# :telephone_receiver: telackbot :telephone_receiver:

A Hubot for [telack][faithcreates-tuesday/telack].

# Usage

```bash
$ # clone repository
$ git clone https://github.com/faithcreates-tuesday/telackbot
$ cd telackbot/

$ # configure
$ export HUBOT_SLACK_TOKEN='...'
$ export HUBOT_TELACK_GOOGLE_EMAIL='...@developer.gserviceaccount.com'
$ export HUBOT_TELACK_GOOGLE_KEY='"-----BEGIN PRIVATE KEY-----\n-----END PRIVATE KEY-----\n"'
$ export HUBOT_TELACK_GOOGLE_SHEET_KEY='...'
$ export HUBOT_TELACK_ROOM='#telack'
$ export HUBOT_TELACK_TELACKBOT='true'

$ # install dependencies
$ npm install

$ # run robot
$ npm start
```

# License

[MIT](LICENSE)

[faithcreates-tuesday/telack]: https://github.com/faithcreates-tuesday/telack
