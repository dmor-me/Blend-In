# Blend In Updates

Release notes for [Blend In](https://blendin.party/), the social deduction party game where everyone knows the word except the Imposter.

## v1.2 — Lobby & Packs Update

**Release date: November 12, 2026**

Describe gets five question packs and the option to bring your own. This update also makes custom word packs easier to create and share, adds in-game Patch Notes, and helps players get back into a lobby after a disconnect.

### Describe question packs

- In Describe mode, a **Question pack** dropdown appears below **Word pack**. **General** keeps the original 12 prompts and is selected by default. Hosts choose one of the five built-in packs or **Custom pack**.
- The lobby shows the selected **Question Pack** separately from the **number of questions** and the **time per question**. Questions are shuffled, with no repeats within a round.
- Hosts can name and rename a custom Describe question pack in **Settings**. The lobby’s **Question Pack** field shows the chosen name, or **Custom pack** if left blank. Built-in pack names stay fixed.

- Paste or import custom questions from a `.txt` file. Use one question per line and separate each answer choice with a vertical bar (`|`). The editor counts unique questions and lets you preview their answer choices before saving.
- Use **Copy AI prompt** to generate questions with a chatbot, or **Export as .txt** to save and share what’s in the editor.

| Pack | Example prompts and answers |
| --- | --- |
| **General** — the original 12 | How much do you enjoy this? → 1–5<br>Which shape best describes this? → Circle / Square / Heart<br>Would you spend $100 on this? → Absolutely / Maybe / Never |
| **Personal** — answer based on your own habits | Would you bring this up unprompted? → Definitely / Only if it came up / Never<br>How much would you miss this? → A lot / A little / Not at all<br>Would your friends be surprised you like this? → Yes / Maybe / No |
| **Close Friends** — pick someone in the lobby | Who here would get most excited about this?<br>Who would make a whole day out of this?<br>Who would change their mind about this first?<br>For each prompt, **pick a player**. |
| **Social** — imagine how the word fits into a group | Would you bring this up in a group chat? → Immediately / With the right group / No<br>Would you suggest this for a group hangout? → Yes / Depends on the group / No<br>Who would you share this with? → One friend / The whole group / Nobody |
| **What If?** — answer a hypothetical | If this disappeared forever, how upset would you be? → Devastated / A little upset / Unbothered<br>If this became twice as common, would that be good? → Better / Same / Worse<br>If you could introduce someone to this, would you? → Absolutely / Depends who / No |

### Custom word pack names and AI prompt

- Hosts can give an imported or pasted word pack a name, such as **Basketball**. The name appears under **Word Pack** in the lobby, while the actual word list stays private. Unnamed packs still appear as **Custom pack**.
- A **Copy AI prompt** button helps hosts draft a word list using the chatbot of their choice. Enter a topic, generate a list, then paste it into the game or import it as a `.txt` file.

- **Export as .txt** saves the words and accepted alternatives currently in the editor, so you can reuse or share the pack.

### In-game Patch Notes

- A circled **!** button opens **What’s New**. The latest released update is shown at the top with its version number, and older notes can be expanded under **Previous updates**.
- **How to play** stays in the main navigation.
- A **Recommend Updates and Report Bugs on GitHub** link below the release history opens the [Blend In issue tracker](https://github.com/dmor-me/Blend-In/issues).

### Interface polish

- The browser tab and site header now share the same SVG logo.
- When the host marks themselves ready, a check appears next to their crown in the player list.

### Lobby reconnects and cleanup

- Clicking the **blendin.** logo from a lobby takes you home and marks you as disconnected, leaving your spot open for **60 seconds**.
- The header shows **Ready to blend** in bright green, **Reconnecting…** in bright yellow while the site restores its connection, and a clickable **Reconnect · 0:42** countdown in bright red when your lobby spot is still held. Each dot pulses gently and stays steady if you prefer reduced motion. The text labels stay visible on mobile.
- A disconnected player gets an amber unplug icon and a **60-second countdown** next to their name. Their name, lobby role, and score stay visible. Returning before the timer expires lets them keep their spot.
- If the host does not return in time, hosting passes to a connected player.
- The public lobby list counts connected players and hides lobbies when nobody is connected. If nobody returns within **two minutes**, the abandoned lobby closes.

## v1.1 — Custom Word Packs Update

**Date: October 18, 2026**

Hosts can bring their own words into the game, from an inside-joke list for friends to a themed pack about basketball, food, or movies.

- Paste words into the custom pack field or import a plain-text `.txt` file. Separate entries with commas or new lines.
- Add alternate names with a vertical bar. For example, `TV|Television` shows **TV** to the players who know the word and accepts either name if the Imposter gets a Last Chance guess.
- Preview the imported entries and their accepted guesses before using the pack.

## v1.0 — Blend In Launch

**Launch date: October 17, 2026**

The first release introduced the core game: create or join a browser lobby, figure out who doesn’t know the secret word, and vote to catch them.

- **Freestyle:** Talk about the word without saying it. Give enough detail to sound convincing without giving the Imposter an easy guess.
- **Describe:** Everyone answers the same multiple-choice questions about the word. Compare the answers, talk through anything suspicious, and vote.
- **Lobbies:** Host a room for **3–20 players**, share an invite link or room code, and choose whether the room appears in the public lobby list.
- **Last Chance:** If the host enables it, a caught Imposter gets one final guess at the secret word and can still steal the round.
