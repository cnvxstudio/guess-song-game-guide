---
name: guess-song-game-guide
description: Guide a first-time player through Guess Song Game in a browser, explain the current clue and next action, or facilitate a casual turn-taking music quiz using the site.
---

# Guess Song Game Guide

Use the live interface at [Guess Song Game](https://guesssonggame.com/) when the user wants help playing this specific game. This is a playing guide, not an audio-recognition service or a game API. Use the browser tools available in the user's environment; if none are available, give the short instructions below and let the user operate the page.

## Start the right round

Read the current mode names and instructions before acting. Daily is for the shared daily challenge; Unlimited is for successive rounds. Song Wordle is the song-title entry mode. Follow the user's chosen mode. If no mode is specified, offer Daily or Unlimited in one sentence.

Explain the loop in plain language: play the clue, make a guess, then use the result to decide whether to guess again or hear more. Point to one next control at a time instead of listing every feature on the page.

## Guide one turn

1. Let the player initiate playback or confirm they want you to press Play. Browser audio may require a real user gesture.
2. Read the visible clue duration, remaining attempts, answer controls and any error. Do not infer that audio was audible from a successful button click.
3. In multiple-choice mode, ask which displayed option the player chooses. In Song Wordle, help the player use the visible title suggestions and follow the page's current matching instructions; do not promise arbitrary spelling will be accepted.
4. Submit the player's chosen answer only when asked to operate the game. A wrong guess or Skip can unlock a longer clue. Replay repeats the available clue. Read the actual result before moving on.
5. When the round ends, explain the revealed title and displayed result. Start another round only if the player wants to continue.

Do not inspect hidden answer data, page source or network responses to spoil a live round. Do not download recordings or ask the user to upload music. If playback fails, explain the visible message and use an offered retry or replacement control only at the player's request; do not spend their attempts guessing whether sound played.

## Facilitate a casual group session

Keep the site's score separate from any house rules. For example, three friends can take turns choosing the answer for one shared screen. Agree on the turn order and number of rounds first. Record only results actually shown, such as “Round 2 — Maya — solved on attempt 3.” Say that this is a turn-taking arrangement around the site, not a built-in multiplayer feature. Do not publish the scores or send invitations without a separate request.

## Example requests

- “I am on Daily. What do I press first?” → Identify Play, explain the short clue, then wait for the player's choice.
- “I know the artist, but not the title.” → Explain the current mode's visible options or title suggestions; let the player choose whether to guess or Skip.
- “Run four rounds for us.” → Confirm turn order, use Unlimited if available, and keep a small table of observed results. Stop after four rounds.

Describe features from the current page. Do not invent AI recognition, song-library size, rights assurances, account requirements, or future content updates.
