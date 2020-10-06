# rolator
### A slackbot to randomly assign team roles to channel members

- Create a .env file that matches the example
- `npm install`
- `npm start`
- Use `ngrok` for local development, this will give you a publicly accessable URL that will forward to localhost. Use this URL in the Slack settings for slash commands, where a URL must be entered for Slack to POST to.
- The only command as of v0.1 is `generate`
- After installing and setting up the bot user within Slack, type `/generate` in the chat to call the bot.
	- [Creating a bot for your workspace](https://slack.com/help/articles/115005265703-Create-a-bot-for-your-workspace)
	- [Enabling interactivity with Slash Commands](https://api.slack.com/interactivity/slash-commands)
