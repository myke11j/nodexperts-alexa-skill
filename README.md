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

- Install node-lambda package, `npm i -g node-lambda`
- `npm i --production` in the working directory
- Create `.env` and `deploy.env` files, follow format from `.env.sample` and `deploy.env.sample` files
- Run `npm run dev:lambda`

#### For local testing

- Create a `event.json` file from `event.json.example` and then run the lambda locally.

## Deploying

For deploying, refer deploy guide on [node-lambda](https://www.npmjs.com/package/node-lambda)

```
npm run dev:lambda-deploy
```