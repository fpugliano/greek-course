# Greek for Sailors 🇬🇷⚓

A free, offline-capable phrasebook Progressive Web App (PWA) for sailors, 
kite surfers, wing foilers, and anyone spending time on or near the water in Greece.

**Live app → [greek.sailingoroboro.com](https://greek.sailingoroboro.com)**

---

## What's in it

10 categories of lessons covering:

- 👋 **Basics** — greetings, introductions, café & restaurant ordering
- 🗺️ **Getting Around** — directions, buses, trains
- 🛒 **Shopping & Services** — groceries, post office
- ⚓ **Maritime & Official** — coast guard, harbour master, Transit Log (AADE), crew list
- 🪁 **Kite Surfing** — beach talk, gear, safety
- 🌊 **Wing Foiling** — discussing the sport, conditions & spots
- 😄 **Ice Breakers** — starting conversations, compliments
- 📖 **Sentence Structure** — phrase breakdowns word by word
- 📝 **Grammar** — key patterns
- 🔢 **Numbers & Time**

Each lesson includes Greek script, romanization, English translation, cultural notes, 
and a multiple-choice quiz.

---

## Features

- 🔊 **Text-to-speech** — tap any phrase to hear it spoken in Greek
- 📱 **Installable PWA** — add to your home screen for offline use
- 🌙 **Dark mode** — automatic, follows system preference
- 🚢 **Sailor-specific content** — Transit Log, crew documentation, coast guard phrases
- 🪁 **Watersports content** — kite surfing and wing foiling vocabulary
- Zero dependencies — pure HTML, CSS, and vanilla JS

---

## How to use

**Online:** Visit [greek.sailingoroboro.com](https://greek.sailingoroboro.com)

**On your phone (iOS):** Open in Safari → Share → Add to Home Screen  
**On your phone (Android):** Open in Chrome → Menu → Add to Home Screen

Once installed it works offline.

---

## Contributing

Contributions are welcome — new phrases, corrections, additional lessons, or translations.

1. Fork the repo
2. Edit `index.html` — all content is in the `lessons` array in the `<script>` section
3. Open a pull request with a clear description of what you changed

Please keep the same data structure for lessons:
```js
{
  cat: 0,              // category index (0–9)
  title: "Lesson name",
  subtitle: "Short description",
  phrases: [
    { greek: "...", roman: "...", english: "...", note: "optional" }
  ],
  tip: "HTML tip text shown at the top of the lesson",
  quiz: [
    { q: "Greek phrase", opts: ["opt1","opt2","opt3","opt4"], a: "correct option" }
  ]
}
```

---

## Project

Built as part of [Oroboro](https://sailingoroboro.com) — a sailing project in the Mediterranean.

---

## License

MIT — see [LICENSE](LICENSE)
