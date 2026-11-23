# Agile Planning Poker

A lightweight, single-file Planning Poker web app for anonymous real-time sprint estimation (up to 10 participants per room).

## Features
* **Zero-friction & anonymous:** Joins via Firebase Anonymous Auth with auto-generated display names.
* **Real-time sync:** Live vote tracking, simultaneous card reveal, and automatic average calculation powered by Cloud Firestore.
* **Custom Fibonacci deck:** `0.1`, `0.25`, `0.5`, `1`, `2`, `3`, `5`, `8`, `13`, `21`, `?`.
* **Auto-cleanup:** Automatically deletes session data when the last participant leaves or after 30 minutes of inactivity.
* **Shareable links:** Supports `?session=<ID>` URL parameters for direct room invites.

## Tech Stack
* HTML5 / Vanilla JS (ES Modules)
* Tailwind CSS (CDN)
* Firebase (Anonymous Auth & Cloud Firestore)