# socialite

Socialite will eventually be a tool for monitoring and posting to multiple social media networks.

## Developing Socialite

To get your socialite development environment runnable, you need to do the following (assuming a working version of node/git):

1. Pull from repository
1. Make sure the database folder exists (`mkdir database`)
1. `npm install`
1. `npm run bowertasks`
1. `cp app/config grant-config.json.template grant-config.json`
1. `cp app/config salt.json.template salt.json`
1. (optional) customize your password salt in `salt.json`
1. Update `grant-config.json` with your API keys
1. `npm run dbtasks`
1. `npm run seed`

![Alpha Screengrab](http://i.imgur.com/65xTmy5.png)
