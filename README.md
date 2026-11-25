# Cyber Quest – safe when AI attacks

A small, free app that walks a household all the way through securing its digital home, now that AI agents make attacks cheap and constant. Two friends play the game: **Ying** (林影), an ethical hacker, tries to sneak in; **Philia** defends your home with you.

- **About 20 questions** about your phone, computers (several, e.g. Linux and Windows on one laptop), accounts, router, smart devices, backups and family → a personal set of quests ("doors").
- **Always a next step:** a card at the top says which quest and which step to do now, with ✓ Done, *Do it with your AI*, or *Can't finish now*. After three doors in one session it suggests stopping on a win.
- **Clear status for every quest:** in progress, to do, blocked or planned (with the blocker and a date), probably fine but not yet checked, done. You tick each step; you can add your own items (e.g. accounts to delete).
- **How hard is your home to get into?** A level per area (devices, accounts, home network, data, people) and Ying's easiest way in.
- **Works with your own AI, all the way.** Menus and scams change every month, so every quest has a prompt for the AI you already use (ChatGPT, Claude, Gemini, Mistral, DeepSeek …). It carries your devices, menu language and the current step, asks the AI to check the steps against the maker's current help pages, and forbids it to ask for passwords or codes. Optional: your own OpenRouter key, stored only on your phone.
- **Upkeep:** a check-up every three months (calendar file), with a check-up prompt for your AI that asks what changed for your devices.
- **Move between devices:** a link or code carries answers, ticks and notes from computer to phone. No server.
- **Spot the trick:** practise on real-world scam messages. 🆘 card for "I think I've been hacked". Printable plan.
- When the last door closes, a short film plays as the finale.

Static, offline PWA, English and German, no accounts, no tracking, no outside requests (except openrouter.ai if you enter your own key). Sources: BSI, Verbraucherzentrale, NCSC (UK), CISA, FBI IC3; checked November 2026. Art made with Google Gemini, original characters. MIT licence.

Files: `index.html` (everything), `sw.js` (offline), `manifest.webmanifest`, `assets/` (art, film, icons).
