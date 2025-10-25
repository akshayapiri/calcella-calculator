# How Calcélla Calculator Works - SUPER SIMPLE EXPLANATION

Imagine you have a calculator in your hands. Let me explain what happens when you press buttons!

## Example: Let's calculate 7 + 5 = ?

### STEP 1: You press "7"
- Calculator thinks: "The user typed 7"
- Screen shows: **"7"**
- Computer memory stores: `currentOperand = "7"`

### STEP 2: You press "+" 
- Calculator thinks: "The user wants to ADD something to 7"
- Screen shows: **"7 +"** (in small text at the top)
- Computer memory stores: 
  - `previousOperand = "7"` (remember this number)
  - `currentOperand = ""` (clear the main screen)
  - `operation = "+"` (remember to add later)

### STEP 3: You press "5"
- Calculator thinks: "The user typed 5"
- Screen shows: **"5"** (in the big number area)
- Computer memory stores: `currentOperand = "5"`

### STEP 4: You press "="
- Calculator thinks: "Time to do the math!"
- Screen shows: **"12"** (the answer!)
- Computer thinks:
  - "I have 7 (previous) + 5 (current) = 12"
  - Let me show 12 on the screen
- Computer memory stores: `currentOperand = "12"`

---

## SIMPLE RULES:

### Rule 1: Number Buttons (0-9 and .)
- When you press a number, it gets added to the screen
- Example: Pressing "3" after "2" makes "23"

### Rule 2: Operation Buttons (+, -, ×, ÷)
- Saves the current number
- Clears the screen to type the next number
- Remembers which operation you want to do

### Rule 3: Equals Button (=)
- Does the actual math
- Shows you the answer

### Rule 4: AC Button (All Clear)
- Clears everything and starts over

### Rule 5: DEL Button (Delete)
- Removes the last number you typed
- Like backspace on your computer

---

## REAL EXAMPLE IN THE COMPUTER'S BRAIN:

```javascript
// When you press "7"
currentOperand = "7"

// When you press "+"
previousOperand = "7"    ← Saves this
currentOperand = ""      ← Clears this
operation = "+"          ← Remembers to add

// When you press "5"
currentOperand = "5"

// When you press "="
// Computer calculates: 7 + 5 = 12
currentOperand = "12"    ← Shows answer
previousOperand = ""     ← Clears old number
operation = undefined    ← No more operation
```

---

## Think of it like:

**The calculator has 3 memory boxes:**

1. **Box 1 (current number)**: The number you see on screen
2. **Box 2 (previous number)**: The number you typed before (hidden)
3. **Box 3 (operation)**: What you want to do (add, subtract, etc.)

When you press "=", it looks in all 3 boxes and does the math!

---

## Why use a Class?

A class is like a blueprint for a calculator. It says:

"You should have these features:
- Store a current number
- Store a previous number  
- Store an operation
- Know how to add numbers
- Know how to subtract
- Know how to display results"

It keeps everything organized and together!
