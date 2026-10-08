# Adder Workbench

A logic circuit workbench where students build a half adder and a full adder from gates, group them into components and see how full adders chain into a ripple-carry adder (OCR A Level Computer Science, H446).

## Features

### Building circuits
- Drag or click to add inputs, AND, OR and XOR gates and named outputs, then wire them up
- A numbered build guide that walks from a half adder to a full adder
- Select gates and **Group → component** to turn them into a reusable block, then duplicate it
- Start from a starting point, a finished half adder, a finished full adder or an empty canvas

### Checking your work
- Live truth table for every output, with working columns for each gate
- Boolean expressions for each output
- Notation in OCR style (∧ ∨ ⊻), words (AND OR XOR) or maths style (. + ⊕)

### Ripple adder
4-bit and 8-bit ripple-carry adders made from full adders
- **Ripple the carry** animates the carry moving from column to column

## How to Use

1. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari). Nothing to install, no login.
2. Follow the build guide on the left to make a half adder
3. Group it, duplicate it, and add a carry in to make a full adder
4. Switch to **Ripple adder** to see full adders chained together

## Use Cases

- A practical lesson building adders from scratch
- Showing why the carry has to ripple
- Linking truth tables, expressions and circuits

## Tech

- A single HTML file: HTML, CSS and plain JavaScript
- No libraries, no build step, no backend
- Uses the browser's local storage to remember your circuit
- Light and dark themes

---

## License

Copyright © Neil Southin. Free for personal use. Schools, colleges, and organisations wishing to use this in classrooms or on a VLE must get in touch first — see [LICENSE.md](LICENSE.md) for full details or email **southinn@colchsfc.ac.uk**.
