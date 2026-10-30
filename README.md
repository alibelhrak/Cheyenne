# 💚 Happy Birthday, Cheyenne

A birthday surprise website made with love for Cheyenne, in her favorite color: green.

**🎁 Open it here: [alibelhrak.github.io/Cheyenne](https://alibelhrak.github.io/Cheyenne/)**

## What's inside

- 💌 **A sealed envelope** that opens with a burst of hearts and confetti
- 🎂 **A birthday cake**: make a wish and tap the candles to blow them out
- 🎈 **Green balloons** floating up the page (tap one to pop it)
- 📸 **Our memories**: photos hanging like polaroids; tap one to see it full screen
- 💌 **A love letter** that writes itself as you scroll
- 💚 **Reasons I love you**: cards to flip, one by one
- 🎆 **Heart-shaped fireworks** and a big beating heart at the end

Hearts float across the whole page, and tapping anywhere sends a little burst of love.

## Files

```
Cheyenne/
├── index.html      the whole website (HTML, CSS, and JavaScript in one file)
├── images/         the photos shown in "Our memories"
│   ├── image1.jpeg
│   └── ... image7.jpeg
└── README.md
```

## Editing

Everything personal is in the `CONFIG` section near the bottom of `index.html`:

| Setting | What it changes |
|---|---|
| `herName` | The name on the envelope, the title, and the browser tab |
| `fromName` | The signature on the letter and in the footer |
| `photos` | Which pictures appear and their captions |
| `letter` | The love letter text |
| `reasons` | The text on the flip cards |
| `finale` | The message under "I love you" |

To add a photo, put it in `images/` and add a line to `photos`:

```js
{ src: "images/image8.jpeg", caption: "Another favorite day" },
```

## Viewing it locally

Open `index.html` in any web browser. No installation needed.

## Hosting

Hosted for free with GitHub Pages (Settings → Pages → branch `main`, folder `/ (root)`). Every push to `main` updates the live site within a few minutes.

---

Made with love by Ali 💚
