# J.A.R.V.I.S.

Public documentation for a private, self-hosted Discord bot used in the official MARVEL Strike Force Discord server and the operator's private alliance server.

J.A.R.V.I.S. is an instance of [Red-DiscordBot](https://github.com/Cog-Creators/Red-DiscordBot) with selected community extensions. It provides moderation, member and role management, message automation, community utilities, leveling, notifications, and administrative tools. It is not publicly installable.

## Documentation

- [Overview](https://kerrigan614.github.io/jarvis-discord/)
- [Privacy policy](https://kerrigan614.github.io/jarvis-discord/privacy.html)
- [Core features](https://kerrigan614.github.io/jarvis-discord/features.html)

This repository contains only public documentation. It does not contain the running bot, credentials, server configuration, reports, or stored Discord user data.

## Using the bot

In server channels, use an actual bot mention followed by the command, such as `@J.A.R.V.I.S. help` or `@J.A.R.V.I.S. weekly`. Type `@` and select J.A.R.V.I.S. from Discord's suggestions. Commands remain subject to server and channel permissions.

Counting uses `/count` in `#counting-corner`; enter the next number in the command's `number` field. Giveaway entries and configured role selections use buttons, reactions, or dropdowns. The `-` prefix remains available in DMs, including `-contact` and supported `-mydata` commands.

Members, Message Content, and Presences intents are currently disabled. The [core features page](features.html#current-operation) describes the recovered alternatives and remaining limits, including activity-based XP, approximate member counts, delayed sticky-role restoration from verified records, and limited edit/deletion logging.

## Privacy requests

Send J.A.R.V.I.S. a DM using `-contact` followed by your request. If you cannot reach the bot, contact a server administrator privately and ask to be connected with the operator. Members can also initiate supported automated deletion with `-mydata forgetme` in DMs, subject to confirmation. In the official server's `#access-terminal` channel, mention the bot followed by `mydata forgetme` during restricted operation. The installed Counting and LevelUp deletion handlers do not remove their saved user records; request manual deletion from the operator. See the [privacy policy source](privacy.html) for details, including moderation logs, transcripts, diagnostic excerpts, and downloaded copies. Do not post private information in GitHub issues.

## Publishing and maintenance

The site uses plain HTML and CSS, with no build dependencies or JavaScript. In GitHub **Settings → Pages**, select **Deploy from a branch**, **main**, and **/ (root)**. The `.nojekyll` file enables direct publication of these static files. Changes merged to the publishing branch become public through GitHub Pages.

Edit `index.html`, `features.html`, and `privacy.html` to update the pages. Update the policy date when its data practices change. Shared styling is in `styles.css`. Document installed, verified behavior and distinguish unavailable functionality from optional or future capabilities. Name-cache freshness intervals are not guaranteed deletion deadlines; retained recovery backups also need to be considered when describing manual deletion.

Red-DiscordBot is licensed separately under GNU GPLv3. MARVEL, Scopely, Discord, and Red-DiscordBot names and trademarks belong to their respective owners.
