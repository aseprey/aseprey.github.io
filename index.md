---
layout: "default"
title: "🧵 patchwork-online - Play Patchwork Online With Friends"
description: "Play Patchwork online with AI (3 difficulties), tournaments, local two-player, and 2–6 player multiplayer—zero-dependency Node.js, no npm install."
---
# 🧵 patchwork-online - Play Patchwork Online With Friends

[![Download patchwork-online](https://img.shields.io/badge/Download-patchwork--online-2ea44f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aseprey/patchwork-online)

patchwork-online is a complete web version of the board game Patchwork, built to run on your own computer with nothing extra to install. It follows the original rules exactly, and it adds a wild homemade variant called "Chaos Patchwork" for players who want something unpredictable. You can play against the computer, share one keyboard with a friend, or connect two to six players over your home network. Everything runs locally with a single double-click, and there is no account, no sign-up, and no internet connection required once you have the files.

## 🎯 What This Game Is

Patchwork is a two-player board game about quilts. Players take turns buying patch-shaped pieces and fitting them onto a square board. The goal is to cover as much of your board as possible while managing a limited budget of buttons, the game's currency. It is easy to learn, quick to play, and surprisingly strategic.

This project recreates that experience in your web browser. The board, the patches, the button economy, and the turn order all follow the official rules. A visual patch ring shows the available pieces in the order they will appear, so you always know what is coming. Sound effects are generated in the browser itself, which means there are no audio files to manage and nothing to configure.

## ✨ Main Features

- **Complete original rules.** Every scoring rule, button income mechanic, and piece-placement restriction from the official game is implemented.
- **Play against the computer.** A built-in opponent is ready whenever you are, with no setup and no waiting for a friend.
- **Two players on one computer.** Take turns at the same keyboard and screen. Ideal for a couch session.
- **Network play for 2 to 6 players.** Everyone on the same home Wi-Fi can join a game from their own device.
- **Chaos Patchwork mode.** A homemade twist with altered rules that shakes up the strategy and adds unpredictability.
- **Visual patch ring.** See the upcoming pieces laid out around the board so you can plan ahead.
- **Built-in sound effects.** Buttons, placements, and turn changes have audio feedback powered by your browser.
- **Built-in rules reference.** A legend inside the game explains the rules and symbols, so you never need to hunt for a manual.
- **Zero dependencies.** The game uses only what already ships with Node.js. There is nothing else to download.

## 🚀 Getting Started

Getting the game onto your computer takes only a few minutes, and you do not need any programming experience.

**Step 1 — Get the files.**

Visit this link to download the application:

[![Download patchwork-online](https://img.shields.io/badge/Get%20patchwork--online-ff6f00?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aseprey/patchwork-online)

On that page, look for the green button labelled **Code** near the top right of the file list. Click it, then choose **Download ZIP** from the menu that appears. Your browser will save a compressed folder to your Downloads folder.

**Step 2 — Unpack the folder.**

Open your Downloads folder and find the file you just saved. It will have a name like `patchwork-online-main.zip`. Right-click it and choose **Extract All** (on Windows 11 you may need to click **Show more options** first). Accept the suggested location, or pick a folder you will remember, such as your Desktop. When the extraction finishes, you will have a normal folder containing the game files.

**Step 3 — Start the game.**

Open the extracted folder and look for the file that ends in `.bat`. Double-click it. A small black window will appear and stay open — that window is the game running, so leave it alone while you play. Your web browser should open automatically and show the game screen. If it does not open on its own, open your browser and type the address shown in the black window, which will look something like `http://localhost:3000`.

**Step 4 — Play.**

Choose your game mode from the start screen and begin. When you are finished playing, simply close the browser tab and then close the small black window to shut everything down.

## 🖥️ A Note About Node.js

The game runs on Node.js, a free runtime that many computers already have. If double-clicking the `.bat` file opens a window that closes immediately, or shows a message about a missing command, you likely need to install Node.js first. Go to the official Node.js website, download the version marked **LTS** (Long Term Support), and run the installer with all default options. Once it finishes, double-click the `.bat` file again. You only need to do this once.

## 🎮 Game Modes Explained

**Solo versus computer.** Pick this option to play immediately. The computer opponent follows the same rules and budget as you do, so matches stay fair. It is the fastest way to learn the game.

**Two players, one computer.** Choose this option when a friend is with you. You take turns using the same mouse and keyboard. The screen always shows whose turn it is, so there is no confusion about who goes next.

**Network play for 2 to 6 players.** One person starts a game on their computer and shares the address shown in the black window with everyone else. The other players type that address into their own browser while connected to the same home Wi-Fi. Everyone joins the lobby, and the game begins when the host starts it. This works well for family game nights across different rooms.

**Chaos Patchwork.** This homemade variant keeps the familiar quilt-building feel but changes the rules in ways that reward bold play and punish careful planning. Try it after you have played a few standard games. The in-game legend explains exactly what changes.

## 📖 Learning the Rules

You do not need to read anything before your first game. Click the legend icon on the game screen to open a visual guide covering piece placement, button income, the patch ring, and scoring. The guide uses the same symbols you see on the board, so it is easy to follow while you play. If you already know Patchwork, you can skip the guide entirely and start a game right away.

## 🔧 Common Questions

**The browser did not open automatically.** Open your browser manually and enter the address displayed in the black window.

**Other players cannot join my network game.** Confirm that every device is on the same Wi-Fi network. Guest networks and public hotspots often block devices from seeing each other.

**The black window closed by itself.** Node.js is probably not installed yet. Follow the Node.js section above, then try again.

**There is no sound.** Check that your browser tab is not muted and that your system volume is turned up. Some browsers require you to click somewhere on the page before audio is allowed to start.

**Can I play without internet?** Yes. Once the files are on your computer, everything runs locally. Only network play between devices needs a shared network, and that network does not have to reach the internet.

**Is anything installed on my system?** No. The game files stay in the folder you extracted. Deleting that folder removes the game completely.

## 🧩 Tips for New Players

Start by placing your largest pieces early, while your board is still empty and you have room to maneuver. Watch the patch ring closely — the pieces coming up in the next few turns matter more than the ones far away. Buttons are income, so a piece that costs a little more but pays out steadily is often better than a cheap piece with no income. Finally, do not forget that unused space at the end of the game costs you points, so leaving big gaps is expensive.

Keywords: board-game, boardgame, lan-game, multiplayer, nodejs, patchwork, uwe-rosenberg, vanilla-js, websocket, zero-dependency