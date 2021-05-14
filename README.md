# Dabble Discord Bot

> Discord bots are AIs that can perform a number of useful automated tasks and Discord bot commands on your server, such as welcoming new members, moderating content, and banning rule breakers.

**DabbleBot is a discord bot which has the following features-**

1. Greet users when they text Hi, Hello etc. in any channel.

![](https://user-images.githubusercontent.com/28767301/118215254-d2cdf200-b48e-11eb-8be9-6993e65bcd16.png)

2. It supports multiple commands to enable users do various things as shown below-

**Following commannds are supported:**

- `$help`: List of all commands

![](https://user-images.githubusercontent.com/28767301/118215252-d2355b80-b48e-11eb-9e67-a9b9884cd3ed.png)

- `$weather [a valid US zip, e.g 10001]`: Returns the weather of the specified US zip,

![](https://user-images.githubusercontent.com/28767301/118215251-d2355b80-b48e-11eb-84b4-7c90b7cf5bd0.png)

- `$nlp [website URL]`: Returns the result of sentiment analysis of the specified URL,

![](https://user-images.githubusercontent.com/28767301/118215249-d1042e80-b48e-11eb-8492-085b5522e1b5.png)

- `$searchImage [item name e.g apple]`: Display an image of the searched item

![](https://user-images.githubusercontent.com/28767301/118215233-ccd81100-b48e-11eb-80bc-e3c00b9b73a6.png)

## How to try this BOT?

You can either run this bot locally and install it in your own discord server or just join my discord servre to play with it.

Here is my discord server, feel free to join it: [https://discord.gg/QheMnETY7j](https://discord.gg/QheMnETY7j)

## Instructions

To develop this discord bot locally, follow the instructions:

1. Install all dependencies:

   `npm i`

2. Create a `.env` same as the `.env.example` file for environment variables in the root directory of this repository, not inside the `src` folder!

3. It will contain these three environment variables:

   - **DISCORDJS_BOT_TOKEN** - Your Bot Token
   - **WEBHOOK_ID** - For webhooks, not required unless you want to use the webhook command
   - **WEBHOOK_TOKEN** - The token for your webhook client
   - **PIXABAY_API_KEY** - For Image Search feature, get it from [here](https://pixabay.com/api/docs/)
   - **MEANINGCLOUD** - For Article's Sentiment Analysis feature, get it from [here](https://www.meaningcloud.com/developer/getting-started)
   - **OPENWEATHER_KEY** - For get Weather information feature, get it from [here](https://openweathermap.org/appid)

4. Run `npm run start` or `npm run dev` in the project directory

## Author

**Shubham Prakash**

🌐 [https://shubhamprakash.dev/](https://shubhamprakash.dev/)
