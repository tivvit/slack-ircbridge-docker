Docker container for [slack-irc](https://github.com/ekmartin/slack-irc)
===

### Run
Copy `slack-irc/config.json.sample` to `slack-irc/config.json` and change the config.

```
docker pull chihchun/slack-ircbridge
docker run -d -t -v ${PWD}/slack-irc:/slack-irc slack-ircbridge
```

### Build from source

Build the docker container or pull from internet

```
docker build -t slack-ircbridge .
```

### Credit
* [slack-irc](https://github.com/ekmartin/slack-irc)
* Docker container for slack-irc https://github.com/caktux/slackbridge
