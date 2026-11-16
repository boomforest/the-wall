# Flow tools

Stuff that keeps us in flow. Take it, improve it, and open an issue or PR if you make a big leap.

---

## The Wall

A post-it wall that sorts itself.

Most to-do apps make you remember to check them. The Wall checks itself. Every note sits in one of four rows, and notes move between rows on their own as time passes:

- **On fire** — overdue, close to its date for how much is at stake, or a trigger date has passed
- **Coming up** — on the radar; turns red by itself when it's time
- **On the wall** — real, no deadline pressing yet
- **Off your brain** — waiting on someone else, or parked on purpose. You're allowed to stop holding it. If its trigger date passes, it comes back red.

**Use it:** https://boomforest.github.io/the-wall/

## The Wall inside Claude (recommended)

`claude.html` is the full version, built to live inside Claude as an artifact so it sits next to your chat. It keeps your notes in Claude's own storage and adds a box on every card: write what you want, then

- **Rearrange card** — Claude changes the dates, triggers and whose move it is, right there on the card.
- **Hand to Virgil** — for real work (emails, research, drafts). The card is marked "With Virgil," and your Claude does it at the start of your next conversation and writes back on the card.

To set it up, tell your Claude: *"Publish https://raw.githubusercontent.com/boomforest/the-wall/main/claude.html as an artifact here, with storage and Claude calls turned on, so it opens beside our chat."*


## The rules

| Stakes | Turns orange | Turns red |
|---|---|---|
| High | 30 days out | 14 days out |
| Medium | 21 days out | 7 days out |
| Low | 10 days out | 3 days out |

A **trigger date** turns a note red on that day no matter what. It's built for "if I haven't heard back by Friday…", the thing that quietly turns from *waiting* into *forgotten*.

## Brain dump

Write everything at once, voice-memo style. Tap **Copy for my AI**, paste into Claude, ChatGPT or any assistant, paste its answer back, and tap **Pin these**. No API keys, no account, works with whatever AI you already use.

## Privacy

It's one HTML file. Your notes are saved in your own browser and never sent anywhere. Use **Download backup** to keep a copy or move to another device.

## Make it yours

Fork it, change the rules, the colors, the rows. Or just download `index.html` and open it.

Made at [Casa de Copas](https://casadecopas.com). MIT licensed.
