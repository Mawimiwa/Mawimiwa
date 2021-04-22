# line-bot-nodejs-starter
starter point to create new line bot project

## How it work
Start express server to handle webhook from LINE

# Install
Clone and run
```
npm install
```
Modify `config.json`
```json
{
  "port" : "3000",
  "channelAccessToken": "09llmwxnP82yYjk0imc2LXXadzQ51MREvSXIvE3R5tIAQ/71apc8JYerpy7Ttu6pcVFGb3B1/q0kw+rRfIezn8GwSeqo9weyRuvyjgH4KZSnMnl1kv0Kj/lD1qWuaM6L39gzm7PGkJvFTlRHxvf7kQdB04t89/1O/w1cDnyilFU=",
  "channelSecret": "246287fe1cd7c653401bfc8d615a15eb"
}
```
Run
```
npm start
```
then you can access [http://localhost:3000](http://localhost:3000)

Use [ngrok](https://ngrok.com/) to expose your local url
```
path/to/ngrok http 3000
```
config webhook url in developer console then enjoy your bot!

## Author
Sitthi Thiammekha
