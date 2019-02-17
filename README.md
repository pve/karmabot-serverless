# karmabot-serverless
Karma Slack bot, made with serverless. 
See https://www.sentialabs.io/2018/08/16/Building-a-Slackbot-with-Serverless-Framework.html

Setting up your local development environment 
(e.g. C9 or local machine or container):

- Check if you already registered your local environment ssh key at github.

- Clone this repo into your local machine

- Install serverless 

```
# Installing the serverless cli
npm install -g serverless
# sls package # set up a new sls package - first time only
```
Setup AWS credentials https://serverless.com/framework/docs/providers/aws/guide/credentials/, 
you will need a deployment user with a policy such as in `sls-policy.json` (or tigher)
```
sls deploy # running on AWS c9 might not need extra permissions.
```

To run this as a bot in Slack, you need some one time configuration in Slack.


BOT_TOKEN for Slack can also be entered in Lambda console (you don't want that in Git).
