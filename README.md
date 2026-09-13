# 💨 FART BUTTON

A hilariously fun web app featuring a big red fart button with 10 different fart sounds!

## 🎮 How to Use

### Main View
Click the **big red button** to play a random fart sound! The button is tempting, red, and begging to be clicked.

### Just The Button View
Click **🔴 Just The Button** for a distraction-free view: one giant red button, nothing else. Every press fires a random fart.

### Soundboard View
Click **🎵 Soundboard** to access all 10 fart sounds. A **← Back** button sits at
the top of the board, so you can always get back to the red button.

1. **Toot** - Short and polite
2. **Squeaker** - High-pitched squeal
3. **Wet One** - Regrettably moist
4. **Dry One** - Crisp and clean
5. **Pull My Finger** - The classic
6. **Ripper** - Tears right through
7. **Trumpet** - Brassy and proud
8. **Bubbler** - Gurgling and ominous
9. **Thunder** - Seven seconds of rumble
10. **The Marathon** - Nine seconds. Commit to it.

### Meme Soundboard View
Click **😎 Memes** for the meme board. It has its own **← Back** button and
grows as sounds are added.

1. **Vine Boom**

**Adding more meme sounds:** drop an MP3 into `sounds/memes/` and add one line
to the `MEMES` array in `index.html`:

```js
const MEMES = [
    { name: 'Vine Boom', file: 'sounds/memes/vine-boom.mp3' },
    { name: 'Your Sound', file: 'sounds/memes/your-sound.mp3' }
];
```

The grid sizes itself to the number of tiles, so no layout changes are needed.

## 🎨 Features

- 🔴 **Big Red Button** - Irresistibly clickable
- 🖤 **Black Background** - Classic dark theme
- 💚 **Animated Green Smoke** - Booger green smoke animation
- 🎵 **10 Real Farts** - Actual recorded audio in `sounds/`, loaded on demand
- 🎯 **Easy Navigation** - Flip between main view and soundboard
- ✨ **Smooth Animations** - Glow effects and transitions

## 🚀 Access the App

**Live at:** https://evobeben.github.io/Fart/

Just click and enjoy! 💨

## 💻 Local Development

```bash
# Clone the repo
git clone https://github.com/EvoBeben/Fart.git
cd Fart

# Serve locally
python3 -m http.server 8000
# Then open http://localhost:8000
```

## 🔊 Sound Credits

The fart sounds are third-party audio, redistributed under their original
licenses. Full attribution and the list of modifications are in [NOTICE](NOTICE).

- Nine sounds derive from the [`terminalfart`](https://www.npmjs.com/package/terminalfart)
  npm package — Apache-2.0, Copyright 2026 Electric Wolfe Marshmallow Hypertext
  (license text in [LICENSE-APACHE-2.0](LICENSE-APACHE-2.0)).
- `pull-my-finger.mp3` derives from the [`pull-my-finger`](https://www.npmjs.com/package/pull-my-finger)
  npm package — MIT.

All files were loudness-normalized, downmixed to mono and re-encoded; `squeaker.mp3`
is additionally pitch-shifted. See [NOTICE](NOTICE) for the per-file mapping.

---

Made with 💨
