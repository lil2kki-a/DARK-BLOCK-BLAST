# DARK-BLOCK-BLAST

## 🇷🇺 Русский

**BLOCK BLAST** — тёмный, меланхоличный клон Block Blast, написанный Дипсиком. Игра с характером: минималистичная, тихая, но с зубами.

### Что это

Классическая механика блок-паззла: перетаскиваешь фигуры на сетку 8×8, собираешь линии, они исчезают. Но под обёрткой — что-то живое. Игра постоянно шепчет тебе. Комментирует твой темп, твои ошибки, твои комбо. Иногда хвалит. Иногда подкалывает. Иногда просто молчит и наблюдает.

### Режимы

- **Классика** — бесконечная игра, чистая гонка за рекордом
- **Ходы** — ограниченное число ходов и целевой счёт. Успей набрать, пока не кончились попытки

### Механики

- **Базовые фигуры** — от одиночного блока до сложных тетрамино и пентамино
- **Спец-блоки:**
  - 💣 **Бомба** — при сгорании линии взрывается радиусом 5×5
  - 🌈 **Радуга** — сжигает все блоки того же цвета на поле
  - ⭐ **Звезда** — даёт +100 очков при сгорании
- **Комбо** — серия очисток подряд даёт множитель до ×3
- **Ghost-preview** — полупрозрачная подсветка, зелёная (можно) или красная (нельзя)
- **Автосохранение** — игра запоминает состояние, можно продолжить позже

### Голос

Центральная фишка — **безымянный голос**, который живёт в игре. Он реагирует на всё: на скорость твоих ходов, на комбо, на проигрыш, на простой. У него сотни реплик в десятках категорий. Он не судья и не тренер — он свидетель. И иногда кажется, что он знает больше, чем говорит.

### Атмосфера

- Тёмный интерфейс с виньеткой и сканлайнами
- Шрифты Special Elite и Cormorant Garamond — машинопись и классическая антиква
- Частицы, вспышки, тряска экрана на крупных комбо
- Три трека в ротации: *AbandonedSector*, *DustyLanterns*, *ShadowedTavern*
- Полный процедурный звук через Web Audio API — каждый клик, взрыв и очистка синтезируются на лету

### Управление

- **Перетаскивание** — мышь или палец
- **R** — рестарт
- **M** — музыка вкл/выкл
- **S** — звуки вкл/выкл

### Технически

Один HTML-файл. Без зависимостей, без сборки. Canvas 2D, Web Audio, localStorage. Работает офлайн (кроме музыкальных треков). Поддерживает тач, свайпы и тап-управление.

---

## 🇬🇧 English

**BLOCK BLAST** — a dark, melancholic Block Blast clone written by DeepSeek. A game with character: minimalist, quiet, but with teeth.

### What it is

Classic block-puzzle mechanics: drag pieces onto an 8×8 grid, complete lines, watch them vanish. But under the hood, something lives. The game keeps whispering to you. It comments on your pace, your mistakes, your combos. Sometimes it praises. Sometimes it taunts. Sometimes it just goes silent and watches.

### Modes

- **Classic** — endless play, pure high-score chase
- **Moves** — limited moves and a target score. Hit the goal before you run out

### Mechanics

- **Base shapes** — from a single block up to complex tetrominoes and pentominoes
- **Special blocks:**
  - 💣 **Bomb** — detonates in a 5×5 radius when its line clears
  - 🌈 **Rainbow** — burns every block of the same color on the board
  - ⭐ **Star** — awards +100 points on clear
- **Combo** — consecutive clears stack a multiplier up to ×3
- **Ghost preview** — translucent highlight, green (fits) or red (doesn't)
- **Autosave** — the game remembers its state; resume anytime

### The Voice

The core gimmick — a **nameless voice** that inhabits the game. It reacts to everything: your move speed, combos, losses, idle time. It has hundreds of lines across dozens of categories. It's not a judge, not a coach — it's a witness. And sometimes it feels like it knows more than it lets on.

### Atmosphere

- Dark UI with vignette and scanlines
- Special Elite + Cormorant Garamond — typewriter and classical serif
- Particles, flashes, screen shake on big combos
- Three rotating tracks: *AbandonedSector*, *DustyLanterns*, *ShadowedTavern*
- Fully procedural audio via Web Audio API — every click, blast and clear is synthesized live

### Controls

- **Drag** — mouse or finger
- **R** — restart
- **M** — toggle music
- **S** — toggle SFX

### Technical

Single HTML file. No dependencies, no build step. Canvas 2D, Web Audio, localStorage. Works offline (except music tracks). Supports touch, swipes and tap input.

---

> *«Ты не боишься проиграть. Это редкость.»*
