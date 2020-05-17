## Experimenting with wire services in LWC OSS

The intent of this repo is to serve as a reference to anyone trying to build their own wire services in lwc-oss framework. This repo is based on this [RFC](https://github.com/salesforce/lwc-rfcs/blob/master/text/0103-wire-adapters.md)

This app merely accepts a subreddit name from the user and fetches the first 10 results and displays the title, with a hyperlink to the page

### Instructions
* npm install
* npx lwc-services build
* npx http-server dist

See the app in action [here](https://surajp.github.io/lwc-oss-wire/dist)
