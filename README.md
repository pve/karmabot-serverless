# karmabot-serverless
Karma Slack bot, made with serverless. See https://www.sentialabs.io/2018/08/16/Building-a-Slackbot-with-Serverless-Framework.html

Setting up your local environment:

Check if you already registered your local environment ssh key at github.
Clone this repo into your local machine

```
Install serverless # Installing the serverless cli
npm install -g serverless
sls package
setup AWS credentials https://serverless.com/framework/docs/providers/aws/guide/credentials/
sls deploy # running on AWS c9 might not need extra permissions.
```

follow more steps.


BOT_TOKEN can also be entered in Lambda console (dont want that in Git)
