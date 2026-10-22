# Slack Drafter

A Mac app for writing whole Slack threads ahead of time. Write the parent message and every reply in one plain text
document, see it exactly as Slack will show it, pick a channel or person, and send. The messages go out in order, as
you, about a second apart.

This repo only hosts the builds. It needs an Apple Silicon Mac.

## Install

1. Download `Slack-Drafter-<version>.dmg` from the [latest release](../../releases/latest).
2. Open it and drag Slack Drafter into Applications.
3. Open the app. macOS says it can't verify it, because the app isn't notarized by Apple. Click Done, then open
   System Settings > Privacy & Security, scroll down and click **Open Anyway** next to Slack Drafter.

## Set up

Click **Connect Slack**, then **Open Slack**. Your browser asks whether Slack Drafter may post as you; click **Allow**
and go back to the app. Add more workspaces from the gear in the bottom-left corner.

## Writing a thread

- A line with only `---` starts the next message. The first message starts the thread and the rest reply to it.
- Slack's formatting works as you'd type it in Slack: `*bold*`, `_italic_`, `~strike~`, `` `code` ``, ` ``` ` blocks,
  `> ` quotes, `-` or `•` bullets and `1.` lists. `@`, `#` and `:` autocomplete people, channels and emoji.
- Paste or drop a screenshot to put it in a message.
- ⌘K picks where it goes, ⌘↩ splits a message at the cursor, and ⌘⇧↩ sends. The ? in the bottom-left corner has the
  full list.

## Updates

The app checks for updates when it opens and every hour, or when you choose Slack Drafter > Check for Updates. When one
is out, the bar at the bottom offers **Download**, then **Restart to update**. Nothing downloads until you click.
