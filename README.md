# 🎮 DIY Simon Says Game (1P & 2P Modes)

A full-on Arduino-based Simon Says memory game with a twist — supports **both 1-player and 2-player modes**, buzzer sounds, a stylish OLED scoreboard, and DIY cardboard buttons. No soldering. No stress. Just plug & play!

## 🧠 Game Concept

Test your memory! Repeat the LED + sound pattern as it grows longer and faster each round. In 2P mode, battle your friend to see who survives longer.

---

## 🔧 Components Used

- Arduino Uno R3
- 0.96" OLED Display (I2C)
- Passive Buzzer (D11)
- 4 LEDs: Red (D2), Green (D3), Blue (D4), Yellow (D5)
- 4 Buttons: Red (D7), Blue (D10), Yellow (D8), Green (D9)
- Breadboard & jumper wires
- Cardboard buttons (DIY style)

---

## 🕹️ How to Play

### 🎛️ Startup & Navigation

- When the game starts, a fancy animation plays, followed by a selection menu.
- You'll see two stars labeled **1P** (1 Player) and **2P** (2 Player).

#### 🔘 Controls for Navigating Menu:
- **⬅️ Red Button (D7)** = Move left  
- **➡️ Blue Button (D10)** = Move right  
- **✅ Green Button (D9)** = Select mode  

---

### 👤 1-Player Mode
- Follow the LED + sound pattern as it grows longer.
- Each correct round = +1 level.
- If you mess up, game over. Your level score is shown on the OLED.

---

### 👥 2-Player Mode
- **Player 1** goes first (Blue button = confirm).
- If they lose, **Player 2** gets their turn (Red button = confirm).
- After both turns, the OLED shows who scored higher and announces the **winner**.
- The winning side glows with a short melody 🎵

---

## 🎨 UI Highlights

- Custom OLED graphics for startup + score screen
- Melody plays for win/loss
- Buttons and LEDs fully synced
- Retro arcade style but fully DIY

---

## 📷 Media (Coming Soon)

![Simon Demo](assets/simon-demo.gif)  
*(Short clip of game in action will go here once added)*

---

## 📦 How to Build

Wiring diagram, pin connections, and full code are included in this repo. Just upload the `.ino` file to your Arduino Uno and you’re good to go.

---

## 🤝 Credits

Project by **@abdulhaadicoder**  
Built with cardboard, passion, and a whole lot of trial & error 💪

---

## ❗ Troubleshooting

### 🟥 LED Not Lighting Up?

If one of your 4 LEDs doesn't light up while the others work fine:

- ✅ First, **double-check your wiring** — is the LED facing the right way? (Long leg = +)
- 🔌 Use a multimeter to **check voltage** coming from the Arduino pin.
- 🔁 Try swapping out the **resistor**. Some LEDs need less resistance to shine properly.
- 🚫 Or just **remove the resistor temporarily** to test — if it lights up then, your resistor was probably too high in value.

Basically, don't panic. It’s always either wiring, voltage, or resistor values. Quick tweaks = game on 🎯

---


