# Assignment 2- CircuitVerse

CircuitVerse project for CS 240 Assignment 2. Hiram Mora Sauceda, RedID 132765669.

## What's in here

- `Assignment2_Gates_and_Adders.cv` - the CircuitVerse project file
- `screenshots/` - screenshots of each circuit and its output
- `Assignment2_Gates_and_Adders_FINAL.pdf` / `.docx` - the write-up I submitted (truth tables, screenshots, explanations)

## How to open it

1. Go to [circuitverse.org](https://circuitverse.org) and sign in.
2. Project > Open Offline (or Import Project) and pick `Assignment2_Gates_and_Adders.cv`.
3. Each circuit is its own tab at the top (A1_Basic_Gates, A2_Custom_Gates, ... C3_Majority_Voter). Click a tab, then click the input switches to test it.

Original hosted project:
https://circuitverse.org/users/460756/projects/assignment-2-gates-and-adders-46016ef2-7d7e-47b2-aa63-e3b3aa9aabf3

## What I did

All the circuits are combinational, so outputs depend only on current inputs, no memory or feedback. I tested each standard and custom gate against its truth table. I also verified the half adder and full adder with every possible input combination before connecting them to build the 4 bit ripple carry adder. Tested the 4 bit adder with six cases, including 0 + 0 as a baseline, and 15 + 1 and 15 + 15 to check carry propagation and overflow. I finally tested the majority voter (my original circuit) using all eight possible input combinations.
