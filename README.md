# J.A.R.V.I.S.

Public documentation for a private, self-hosted Discord bot used in the official MARVEL Strike Force Discord server and the operator's private alliance server.

J.A.R.V.I.S. is an instance of [Red-DiscordBot](https://github.com/Cog-Creators/Red-DiscordBot) with selected community extensions. It provides moderation, member and role management, message automation, community utilities, leveling, notifications, and administrative tools. It is not publicly installable.

## Documentation

- [Overview](https://kerrigan614.github.io/jarvis-discord/)
- [Privacy policy](https://kerrigan614.github.io/jarvis-discord/privacy.html)
- [Core features](https://kerrigan614.github.io/jarvis-discord/features.html)

This repository contains only public documentation. It does not contain the running bot, credentials, server configuration, reports, or stored Discord user data.

## Using the bot

Use the `-` prefix in server channels or DMs, such as `-help` or `-weekly`. Server commands also accept an actual bot mention followed by the command, such as `@J.A.R.V.I.S. help`. Type `@` and select J.A.R.V.I.S. from Discord's suggestions. Commands remain subject to server and channel permissions.

Counting accepts ordinary numbers in `#counting-corner` again. The optional `/count` command also accepts the next number in its `number` field. Both methods share the same sequence and turn rules. Giveaway entries and configured role selections use buttons, reactions, or dropdowns.

Members and Message Content intents were restored and enabled on November 25, 2026. Presences remains disabled. The [core features page](features.html#current-operation) describes current operation, including content-based XP checks, ordinary-number counting, native member-event handling, and configured moderation logging. Recovery fallbacks remain installed for a future loss of access; permanent name, host-attribution, and counting fixes remain active.

## Privacy requests

Send J.A.R.V.I.S. a DM using `-contact` followed by your request. If you cannot reach the bot, contact a server administrator privately and ask to be connected with the operator. Members can also initiate supported automated deletion with `-mydata forgetme` in DMs, subject to confirmation. In the official server's `#access-terminal` channel, use `-mydata forgetme` or mention the bot followed by `mydata forgetme`. The installed Counting and LevelUp deletion handlers do not remove their saved user records; request manual deletion from the operator. See the [privacy policy source](privacy.html) for details, including moderation logs, transcripts, diagnostic excerpts, and downloaded copies. Do not post private information in GitHub issues.

## Publishing and maintenance

The site uses plain HTML and CSS, with no build dependencies or JavaScript. In GitHub **Settings → Pages**, select **Deploy from a branch**, **main**, and **/ (root)**. The `.nojekyll` file enables direct publication of these static files. Changes merged to the publishing branch become public through GitHub Pages.

Edit `index.html`, `features.html`, and `privacy.html` to update the pages. Update the policy date when its data practices change. Shared styling is in `styles.css`. Document installed behavior and distinguish source-supported functionality from completed live testing. Name-cache freshness intervals are not guaranteed deletion deadlines; retained recovery backups also need to be considered when describing manual deletion.

Discord's [App Verification](https://support-dev.discord.com/hc/en-us/articles/23926564536471-How-Do-I-Get-My-App-Verified) for scaling beyond 100 servers is separate from [Privileged Intent review](https://support-dev.discord.com/hc/en-us/articles/40281523410967-Changes-to-Privileged-Intent-Access-for-Discord-Apps). J.A.R.V.I.S. remains private to two servers. Its approved intent access is subject to Discord's annual review process; follow Developer Portal, email, and system-DM notices. App Verification is not being pursued for this private deployment, and no install link is published.

Red-DiscordBot is licensed separately under GNU GPLv3. MARVEL, Scopely, Discord, and Red-DiscordBot names and trademarks belong to their respective owners.
