# Assignment 2 - Gates and Adders

CircuitVerse project for CS 240 Assignment 2 (Module 2: Combinational Logic).
Author: Hiram Mora Sauceda (RedID 132765669)

## What this is

A CircuitVerse project containing 11 combinational-logic circuits, covering:

- **Part A - Gates**: all 7 basic logic gates (AND, OR, XOR, XNOR, NAND, NOR, NOT), plus
  custom-built NAND/NOR/XNOR gates made only from AND, OR, and NOT.
- **Part B - Displays**: a manually-wired hex display, a "smart" hex display, RGB LEDs set
  to SDSU Red, a randomized RGB LED, a randomized RGB matrix, and a smiley face on an RGB
  matrix.
- **Part C - Advanced Logic**: a half adder, a full adder, a 4-bit ripple-carry adder, and
  an original circuit (a 3-input majority voter).

## Files

- `Assignment2_Gates_and_Adders.cv` - the raw CircuitVerse project file (JSON). This is the
  project's source file, exported directly from CircuitVerse.
- `screenshots/` - screenshots of every circuit and its tested output.
- `Assignment2_Gates_and_Adders_FINAL.pdf` / `.docx` - the full write-up submitted through
  Canvas: design explanation, truth tables, a readable circuit/element listing, and all
  screenshots.

## How to run / view it

1. Go to [circuitverse.org](https://circuitverse.org) and sign in (a free account works).
2. Click **Project > Open Offline** (or **Import Project**) in the simulator and select
   `Assignment2_Gates_and_Adders.cv`.
3. Each circuit is its own tab across the top of the simulator (A1_Basic_Gates,
   A2_Custom_Gates, B1_Manual_Hex, ... C3_Majority_Voter). Click a tab to open that circuit,
   then click the input switches to change values and watch the outputs update live.

Alternatively, the original hosted project is viewable directly at:
https://circuitverse.org/users/460756/projects/assignment-2-gates-and-adders-46016ef2-7d7e-47b2-aa63-e3b3aa9aabf3

## Design notes

All circuits are combinational: outputs depend only on the current inputs, with no memory
or feedback. Each gate (standard and custom) was tested against its truth table; the half
adder and full adder were verified against every input combination before being chained
into the 4-bit ripple-carry adder, which was tested with 6 cases including a baseline
(0 + 0), and carry-propagation/overflow cases (15 + 1, 15 + 15). The majority voter (the
original circuit) was tested against all 8 input combinations.

See the PDF/DOCX write-up for full truth tables and a readable listing of every circuit's
elements.
