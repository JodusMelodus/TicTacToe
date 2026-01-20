# Tic Tac Toe

## 📜 Backstory

In 2020, while South Africa was in the middle of the COVID-19 lockdown, I was in my final year of middle school.
My cousin, who was taking IT in high school, introduced me to the world of programming.

I was immediately hooked.
I spent countless afternoons debugging and dedicated my Sundays to sitting with my dad, piecing together the logic for this game.
It was my first ever project, built using **Delphi(Pascal)** - the standard in the South African school system.
This project didn't just result in a game; it sparked the passion for software development that I still carry to this day.

## 🛠️ Tech Stack

- **Language:** Delphi(pascal)
- **IDE:** RAD Studio / Delphi
- **Platform:** Windows VCL Application

## 🚀 Features

- **Two-Player Logic:** Classic X vs O gameplay.
- **Win Detection:** Hard-coded because I was a newbie.
- **Singleplayer & Multiplayer:** Randomized AI
- **Themes:** Because I thought it was cool.
- **Input validation:** Ensures only valid moves.

## 📸 Preview

<img width="469" height="212" alt="image" src="https://github.com/user-attachments/assets/0778274b-a1d4-48bb-856e-904c6d3e6ba6" />

## 🧠 Big Brain Moments (2020 Edition)

We all start somewhere. Before I understood clean code, I practiced "Creative Logic".
Here are some of my favorite artifacts from the original source code:

### 1. `Char` isn't a datatype
Why use a single character when you can reserve space for five?
I clearly didn't know anything about datatypes and sizes.

```pascal
var
    varChar:string[5]
```

### 2. "Consistent" Formatting
My "Shift" key was working overtime, but only half the time.
I pioneered a new style of "Schrödinger’s Case Sensitivity" - where `BEGIN` is loud, but `Begin` is polite, and `Procedure` is fancy.

```pascal
procedure pToggleValue();
BEGIN
  if varChar = 'X' then varChar := 'O' ELSE varChar := 'X';
END;

Procedure pCheckWin (Out IsWinner:Boolean);
Begin
```

### 3. The `If-Then-Else` Marathon

I was totally unaware that `case` (Switch) statements existed, leading to only a "few" `if` statements. 

### 4. The Loneliest Comment
In case I forgot what I just wrote only a few centimetres to the left, I made sure to clarify it for my future self.
This is peak documentation.

```pascal
Screen.Cursor := crHourGlass;                                                 //cursor := crHourglass
```