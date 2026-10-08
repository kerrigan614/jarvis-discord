# J.A.R.V.I.S.

Public documentation for a private, self-hosted Discord bot used in the official MARVEL Strike Force Discord server and the operator's private alliance server.

J.A.R.V.I.S. is an instance of [Red-DiscordBot](https://github.com/Cog-Creators/Red-DiscordBot) with selected community extensions. It provides moderation, member and role management, message automation, community utilities, leveling, notifications, and administrative tools. It is not publicly installable.

## Documentation

- [Overview](https://kerrigan614.github.io/jarvis-discord/)
- [Privacy policy](https://kerrigan614.github.io/jarvis-discord/privacy.html)
- [Core features](https://kerrigan614.github.io/jarvis-discord/features.html)

This repository contains only public documentation. It does not contain the running bot, credentials, server configuration, reports, or stored Discord user data.

## Privacy requests

Send J.A.R.V.I.S. a DM using `-contact` followed by your request. If you cannot reach the bot, contact a server administrator privately and ask to be connected with the operator. Members can also use `-mydata forgetme` in DMs or in the official server's `#access-terminal` channel, subject to confirmation. See the [privacy policy source](privacy.html) for deletion details and limitations, including moderation logs, transcripts, and downloaded copies. Do not post private information in GitHub issues.

## Publishing and maintenance

The site uses plain HTML and CSS, with no build dependencies or JavaScript. In GitHub **Settings → Pages**, select **Deploy from a branch**, **main**, and **/ (root)**. The `.nojekyll` file enables direct publication of these static files.

Edit `index.html`, `features.html`, and `privacy.html` to update the pages. Update the policy date when its data practices change. Shared styling is in `styles.css`.

Red-DiscordBot is licensed separately under GNU GPLv3. MARVEL, Scopely, Discord, and Red-DiscordBot names and trademarks belong to their respective owners.
