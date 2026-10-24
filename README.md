# UpDrafter

A Mac app for writing whole Slack threads ahead of time. Write the parent message and every reply in one plain text
document, see it exactly as Slack will show it, pick a channel or person, and send. The messages go out in order, as
you, about a second apart. It used to be called Slack Drafter.

This repo only hosts the builds. It needs an Apple Silicon Mac.

## Install

1. Download `UpDrafter-<version>.dmg` from the [latest release](../../releases/latest).
2. Open it and drag UpDrafter into Applications. If you had Slack Drafter, move it to the Bin; your drafts and
   workspaces carry over.
3. Open the app. macOS says it can't verify it, because the app isn't notarized by Apple. Click Done, then open
   System Settings > Privacy & Security, scroll down and click **Open Anyway** next to UpDrafter.

## Set up

Click **Connect Slack**, then **Open Slack**. Your browser asks whether the app may post as you; click **Allow** and go
back to UpDrafter. Add more workspaces with the **+** in the rail on the left, and switch between them there, like in
Slack.

## Writing a thread

- A line with only `---` or `...` starts the next message. The first message starts the thread and the rest reply to
  it. Typing one on an empty line moves you straight into the next message.
- Slack's formatting works as you'd type it in Slack: `*bold*`, `_italic_`, `~strike~`, `` `code` ``, ` ``` ` blocks,
  `> ` quotes, `-` or `•` bullets and `1.` lists. `@`, `#` and `:` autocomplete people, channels and emoji.
- Attach any file with the paperclip under the editor, or paste or drop it in. Images show in the preview; other files
  show as a card.
- ⌘K picks where it goes, ⌘↩ splits a message at the cursor, and ⌘⇧↩ sends. The **?** at the bottom of the left
  rail has the full list.
- Drag the lines between the columns to resize them.

## Scheduling

The arrow next to **Send** schedules a thread for tomorrow morning, Monday morning or a time you pick. UpDrafter sends
it itself, not Slack, so it only goes out if the app is running and your Mac is awake at that time. Closing the window
is fine; quitting the app isn't. If it misses its time, it waits for you to send it, pick a new time or cancel.

## Updates

The app checks for updates when it opens and every hour, or when you choose UpDrafter > Check for Updates. When one is
out, the bar under the draft list offers **Download**, then **Restart to update**. Nothing downloads until you click.
