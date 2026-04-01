# Duel Tracker

A two-player Yu-Gi-Oh! life point tracker. Supports adding, subtracting, and halving LP, plus a dice roller, coin flip, and duel log.

- No ads, ever
- Works fully offline once installed

---

## Installing on iPhone

1. Open **Safari** and navigate to the app URL
2. Tap the **Share** button at the bottom of the screen (the box with an arrow pointing up)
3. Scroll down in the share sheet and tap **"Add to Home Screen"**
4. Tap **Add** in the top right corner
5. The app will appear on your home screen and open full screen like a native app

> **Important:** This must be done in Safari. Chrome and other browsers on iPhone do not support adding PWAs to the home screen.

---

## Installing on Android

1. Open **Chrome** and navigate to the app URL
2. Tap the **three-dot menu** in the top right corner
3. Tap **"Add to Home screen"**
4. Tap **Add** on the confirmation prompt
5. The app will appear on your home screen like a native app

> Chrome may also automatically show a banner at the bottom of the screen prompting you to install — you can tap that instead.

---

## How to Use

The screen is split in two — Duelist 1 on the bottom, Duelist 2 on the top (rotated to face them). Each side is independent.

- Tap either duelist's life point total to open the edit sheet
- Choose **− SUB** to subtract, **+ ADD** to add, or **÷ HALF** to halve their LP
- Enter an amount using the numpad and tap **CONFIRM**
- Tap **🎲** to roll a dice
- Tap **🪙** to flip a coin
- Tap **📜** to view the duel log for that duelist's side
- Tap the **☰ menu button** in the centre of the screen for more options:
  - **INSTALL** — instructions for adding the app to your home screen
  - **RESET DUEL** — restarts both players at 8000 LP and clears the log

---

## Editing Life Points

Tapping a duelist's LP total slides up (or down for Duelist 2) an edit sheet with three modes:

- **− SUB** — subtract from the duelist's LP
- **+ ADD** — add to the duelist's LP
- **÷ HALF** — halve the duelist's LP (numpad dims; tap CONFIRM to apply)

Use the numpad to enter an amount, then tap **CONFIRM**. The preview line shows what the resulting LP will be before you confirm.

When a duelist reaches 0 LP, their card reads **SENT TO THE SHADOW REALM**.

---

## Dice & Coin

Each duelist has their own 🎲 and 🪙 buttons. The result appears as a card in the centre of the screen, readable by both players — one side is rotated 180° for the duelist on the opposite end. Tap anywhere to dismiss.

Results are recorded in the duel log under the duelist who triggered them.

---

## Duel Log

The **📜** button opens a running log of every life point change, dice roll, and coin flip made during the current duel. Each entry shows the player, what happened, and the result:

```
DUELIST 1 → -2000 → 6000
DUELIST 2 → ÷2    → 4000
DUELIST 1 → +500  → 6500
DUELIST 2 → ROLL  → THREE
DUELIST 1 → FLIP  → HEADS
```

- Subtractions and halves are shown in **red**
- Additions are shown in **green**
- Dice rolls and coin flips are shown in **amber**
- The log is ordered newest first
- Tapping **RESET DUEL** clears the log along with both players' LP
