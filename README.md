# 🐱 Nyan Cat Batch

A recreation of the iconic **Nyan Cat** animation entirely in **Windows Batch (.bat)** using Unicode full block characters to simulate pixel art.

This project explores how far the Windows Command Prompt can be pushed, recreating an animated character with surprisingly few resources.

> 🚧 **Work in Progress**  
> The animation is still being improved and is not yet a complete recreation of the original.

---

# 🎬 Preview

> *(GIFs and screenshots will be added here.)*

---

# ✨ Features

- 🟩 Pixel-art graphics rendered using Unicode full block (`█`) characters
- 🖥️ Runs directly inside Windows Command Prompt
- ⚡ Written primarily in Windows Batch, with a small amount of PowerShell used for supporting tasks
- 🎬 Built-in comparison between the original animation and the Batch recreation
- 🎵 Includes a fan-made MIDI recreation that can be played with any General MIDI compatible synthesizer
- 📦 No external libraries required

---

# ⚙️ Requirements

- Windows 10/11
- Command Prompt (CMD)
- PowerShell
- UTF-8 compatible console (recommended)

---

# ▶️ Running

1. Clone or download this repository.
2. Open the project folder.
3. Run:

```bat
NyanBATCH.bat
```

The comparison sequence is displayed automatically before the animation begins.

---

# 🛠️ How It Works

The animation is rendered frame-by-frame inside the Windows Command Prompt.

Instead of displaying images, the project draws each frame using Unicode **full block (`█`) characters**, creating a pixel-art effect directly in the console.

Most of the project is written entirely in Batch scripting, with a small amount of PowerShell used for helper tasks that are difficult or impractical to perform in pure Batch.

---

# 🖥️ Recommended Console

For the best experience, use:

- Windows Terminal
- Windows Command Prompt
- Consolas font
- Cascadia Mono font

Other terminals may render Unicode block characters differently.

---

# ⚠️ Accessibility Notice

## Photosensitive Epilepsy Warning

**WARNING**

This project contains a rapidly updating console animation that may produce flashing or flickering effects.

Individuals with photosensitive epilepsy or sensitivity to flashing lights should use caution before running this program.

To ensure users have time to read this warning, the application waits **20–30 seconds** before starting the animation.

---

# 🎵 Music

This repository includes a **fan-made MIDI recreation** of the original Nyan Cat music.

The MIDI file was created for this project and can be played using any **General MIDI compatible synthesizer**.

No original recordings or audio files are included.

---

# ❤️ Credits

### Original Music

The original **Nyan Cat** melody was composed by **DaniwellP**.

### Original Character

Nyan Cat was created by **Chris Torres (PRguitarman)**.

This project is an unofficial, non-commercial fan recreation made for educational and entertainment purposes.

All rights to the original character, artwork, and music belong to their respective copyright holders.

---

# 📜 License

This project is licensed under the MIT License.

The MIT License applies to the source code in this repository.

Third-party content (including the Nyan Cat character, artwork, and music) is not covered by this license and remains the property of their respective copyright holders.

---

# 🎯 Goal

The purpose of this project is to explore the capabilities and limitations of Windows Batch scripting by recreating a well-known animated meme using only console graphics.

---

Made with ❤️ using Windows Batch.
