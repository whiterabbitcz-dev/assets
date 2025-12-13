# White Rabbit: Social Sprint - Level 4

🐰 Webová hra vytvořená ve frameworku **Phaser 3**

## 🎮 Hrát online

**[Hrát hru zde](https://VASE-GITHUB-USERNAME.github.io/REPOSITORY-NAME/)**

_(Po nahrání na GitHub nahraďte link výše vaším skutečným odkazem)_

## 📖 O hře

White Rabbit běží social media světem! Vaším úkolem je skákat přes překážky a přežít co nejdéle.

### Ovládání
- **Desktop**: `SPACE` nebo `↑` (šipka nahoru) pro skok
- **Mobile**: Tapněte kamkoliv na obrazovku
- **Double Jump**: Můžete skočit podruhé ve vzduchu!

## 🚀 Lokální spuštění

### Metoda 1: Přes HTTP server (doporučeno)

```bash
# Python 3
python3 -m http.server 8000

# Nebo Node.js
npx serve
```

Poté otevřete prohlížeč na `http://localhost:8000`

### Metoda 2: Přímé otevření
Dvojklik na `index.html` (může nefungovat kvůli CORS)

## 🛠️ Technologie

- **Framework**: Phaser 3.70.0
- **Physics**: Arcade Physics
- **Assets**: Custom sprite sheets & backgrounds

## 📂 Struktura souborů

```
/
├── index.html              # Hlavní herní soubor
├── bg_level4.png          # Pozadí levelu
├── rabbit_spritesheet.png # Sprite sheet hlavní postavy
└── README.md              # Tento soubor
```

## 🐛 Debug mód

Pro aktivaci debug módu otevřete `index.html` a změňte:

```javascript
const DEBUG_MODE = true;  // řádek 38
```

Debug mód zobrazuje:
- FPS counter
- Pozici a velocity hráče
- Frame animací
- Hitboxy

## 📝 Licence

© 2025 White Rabbit Game

---

Vytvořeno s ❤️ a **Phaser 3**

