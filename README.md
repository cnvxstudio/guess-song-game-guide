# Guess Song Game Guide

A reusable, text-only agent skill for explaining and playing [Guess Song Game](https://guesssonggame.com/) through its visible browser interface.

Maintained by the Guess Song Game product team. This repository contains a playing guide, not the game source code, a music library, an audio-recognition model, or an API.

## Use the skill

Read [SKILL.md](SKILL.md), or place this folder in the skills directory supported by your agent. A browser-capable agent can explain the current mode, point to the next control, and operate a round when the player asks. Without browser access, it can provide the short instructions and let the player operate the page.

Example requests:

- “Explain Daily mode one step at a time.”
- “Show me how title suggestions work in Song Wordle.”
- “Help three friends take turns for four rounds.”

The guide follows the live interface, asks for the player's own answer, and reads actual results. It does not inspect hidden answers, download recordings, promise that a click produced audible sound, or claim that turn-taking is built-in multiplayer.

## Requirements

An instruction-following agent. Browser access is optional for explanation and necessary for operating the website. No API keys, scripts, package installation, or access to private files is required by this guide.

## License

MIT. The license covers the text in this repository. It does not license third-party songs, recordings, or other content available through the website.
