# nodexperts-alexa-skill
An alexa skill for asking direct question to NodeXperts

Ask questions like

```
Tell me about Node experts?
Who are partners of node experts?
How many developers node experts have?
Where is node experts office located? 
Which projects node experts have worked on?
```

## Set up

There are two scripts in package.json, for
 - running lambda locally
 - deploying lambda to AWS

```
    "dev:lambda": ". ./env-variables.sh && node-lambda run",
    "dev:lambda-deploy": "bash deploy.sh"
```

As you can see, you will need either one of the above specified files.
There is `env-variables.sh.example` file, follow it to create your own `env-variable.sh` file.

## Deploying

For deploying, refer deploy guide on [node-lambda](https://www.npmjs.com/package/node-lambda)