# Instructions

To develop this discord bot locally, follow the instructions:

1. Install all dependencies:

   `npm i`

2. Create a `.env` same as the `.env.example` file for environment variables in the root directory of this repository, not inside the `src` folder!

3. It will contain these three environment variables:

   - **DISCORDJS_BOT_TOKEN** - Your Bot Token
   - **WEBHOOK_ID** - For webhooks, not required unless you want to use the webhook command
   - **WEBHOOK_TOKEN** - The token for your webhook client

4. Run `npm run start` or `npm run dev` in the project directory
