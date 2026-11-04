# PrivChat Web

The web version of PrivChat, a private chat app. This folder is a Firebase Hosting site (see `firebase.json`) with Firestore security rules (`firestore.rules`) that control who can read and write chat data.

## What's inside

- `public/` - the website files that Firebase Hosting serves.
- `firebase.json` - Firebase Hosting configuration.
- `firestore.rules` - Firestore security rules.

## Deploying

Install the Firebase CLI, log in, and deploy from this folder:

    firebase deploy

The site is hosted on Firebase at `privchat0.web.app`.

*This repository includes configuration and secrets files. Keep it private.*