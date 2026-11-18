# Privacy Policy — SketchingRoom Discord bot

**Last updated:** 17 November 2026
**Applies to:** the SketchingRoom Discord bot ("the Bot")
**Operator:** SketchingRoom ("we", "us", "our")
**Contact:** https://sketchingroom.com

> The Bot is an independent tool built by SketchingRoom. It is not made by, endorsed by, or affiliated with Discord Inc.

## 1. Summary

The Bot helps artists run commission work inside a Discord server: it turns briefs into private threads, manages a commission queue, posts review updates from a SketchingRoom workspace, and offers image tools. To do that, it stores a small amount of data. This policy says exactly what.

## 2. What we collect

| Data | Why | Where it lives |
| --- | --- | --- |
| Discord identifiers — your user ID, server ID, and the channel/thread IDs you interact with | Route messages, decide who may act on a commission, keep features working after restarts | Bot database |
| Commission briefs — title, brief text, budget, deadline, usage rights you submit through `/commission` | Create and run the commission thread | Bot database; also the artist's SketchingRoom workspace when the server has connected one |
| Revision requests — the note you submit when you press "Request revision" | Revision tracking and revision-limit enforcement | Bot database; also the workspace when connected |
| Queue data — user ID, optional note, status, timestamps | Waitlist and slot promotion | Bot database |
| Commission workflow metadata — status, revision count, linked workspace reference, timestamps | Show the commission card and keep threads in sync | Bot database |
| Review sync data — workspace commission reference, status, version numbers, preview and review URLs, deposit-paid flag | Post review updates into the right thread | Bot database |
| Portfolio crossposting — attachments and captions from the channel a server admin designates as the portfolio channel | Repost finished work to the announcements channel | Bot database stores only message IDs, to avoid duplicate posts |
| Images you invoke the watermark or palette tool on | Produce a watermarked preview or colour palette | Processed in memory and returned to you; **not written to disk and not retained** |
| Server configuration — channel IDs, client role ID, slot count, artist workspace slug | Make the features work in that server | Bot database |
| Operational logs — errors, timestamps, identifiers | Debugging and abuse prevention | Host logs |

We do not require an email address, payment details or government identity to use the Bot.

## 3. What we do not collect

- We do not read or store general chat, direct messages, or messages in channels other than the designated portfolio channel.
- We do not process or store commission payments. Payment happens outside Discord and outside the Bot.
- We do not use advertising or analytics trackers, do not build advertising profiles, do not sell or rent personal data, and do not use your content to train machine-learning models.

**Note on message content.** The Bot requests Discord's Message Content privileged intent. Our code evaluates message content only in the designated portfolio channel (to read captions) and in the forms and threads where you submit briefs and revision notes. Other message content is discarded without being read or stored.

## 4. Who we share it with

- **Discord Inc.** — the platform that carries the messages. Discord's own Privacy Policy applies to its processing.
- **The artist's SketchingRoom workspace** — only for the data listed above, and only when the server has connected a workspace.
- **Our hosting provider** — which runs the Bot process and database.

We do not sell personal data and do not share it for advertising. We may disclose data where legally required.

## 5. Legal bases (EEA and UK)

- **Contract / steps at your request** — running the commission workflow you asked for.
- **Legitimate interests** — operating the queue, preventing abuse, security and debugging.
- **Consent** — where we specifically ask for it.
- **Legal obligation** — where applicable.

## 6. Retention

- Queue entries remain until they are completed or cancelled, and may be kept for queue history.
- Commission records remain while the commission is active and afterwards for the artist's records, unless you ask us to delete them.
- Images are never retained.
- Logs are kept only as long as needed to operate and secure the Bot.
- If the Bot is removed from a server we stop collecting new data. Existing records remain until deleted on request or by routine cleanup.

## 7. Your rights and choices

- Run `/privacy` in the server to see the counts of what we hold about you there.
- Contact us at the address above to request access, correction, export or deletion of your data.
- **EEA/UK:** you may also object to processing based on legitimate interests and lodge a complaint with your local data-protection authority.
- **California:** we do not sell or share personal information as those terms are defined by the CCPA/CPRA.

We respond within the time required by applicable law.

## 8. Security

We use reasonable technical measures: least-privilege bot permissions, token-based access to the SketchingRoom API, and data stored in a database on the host that runs the Bot. No system is perfectly secure and we cannot guarantee absolute security.

## 9. Children

The Bot is not directed at children. Discord requires users to be at least 13, or the minimum age in their country. If you believe a child has provided data to us, contact us and we will delete it.

## 10. International transfers

The Bot and its database may be hosted outside your country, and Discord processes data in the regions described in its own policy. Data may therefore be processed outside your country of residence.

## 11. Changes

We may update this policy. The "last updated" date reflects the current version, and material changes will be announced in the server where practical.

## 12. Contact

SketchingRoom — https://sketchingroom.com
