# notesapp

A single-page notes app in plain JavaScript, built in August 2021 (commits 2021-08-11 to 2021-08-14).

## What it is

A static HTML page (Bootstrap for layout) where you type a note, click "Add Note", and it's saved to `localStorage`. Notes render as cards with a delete button, and a search box filters visible cards by substring match. No backend — everything lives in the browser's local storage, so notes don't sync across devices or browsers.

## Stack

- Plain HTML/CSS/JavaScript (no framework, no build step)
- Bootstrap for styling
- Browser `localStorage` for persistence

## Running it

Open `index.html` directly in a browser — no server or build step required. Verified by reading the code; the app has no dependencies to install.

## Status

Written in August 2021 as an early practice project for DOM manipulation and `localStorage`. Not maintained. The author left a "Further Features" wishlist in the code (titles, marking notes important, per-user notes, server sync) that was never implemented.
