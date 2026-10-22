# ChatTree: downloads for early testers

ChatTree turns your conversations with Claude into a visual map of ideas, next to a built-in terminal that runs your own Claude Code.

This repository only holds ChatTree's downloads and its update feed (no source code).

## Install

1. Download the latest `ChatTree-<version>.dmg` from [Releases](https://github.com/Koza101/chattree-releases/releases/latest).
2. Open it and drag ChatTree into Applications.
3. This early build isn't signed with an Apple Developer ID yet, so macOS asks you to allow it once: open ChatTree, click **Done**, then go to **System Settings → Privacy & Security** and click **Open Anyway** next to the ChatTree message.

After that, updates install from inside the app (**ChatTree → Check for Updates…**).

## Requirements

- A Mac with Apple silicon (M1 or later), macOS 14 or later
- Claude Code, signed in with your own Claude account
- Optional: Apple Intelligence, for better labels when building maps of older sessions

## Privacy

Your maps are files on your Mac (`~/Library/Application Support/ChatTree`). ChatTree has no account and no server, and never sees your Claude sign-in. Nothing is sent anywhere, except when you choose "Organize with Claude", which sends that one conversation to Claude using your own API key.

ChatTree runs Claude Code; it isn't made by or affiliated with Anthropic.
