LogicSim — Digital Logic Gate Simulator 

An interactive browser-based simulator for digital logic gates, built as a learning tool for ECM and ECE students studying Digital Electronics. Visualises gate behaviour with real-time input toggling and live truth tables.

## Features
- 7 gates: AND, OR, NOT, NAND, NOR, XOR, XNOR
-  Real-time input toggling with animated wire state changes
- Live truth table with current input row highlighted
- SVG gate symbol rendering for each gate type
- Boolean expression displayed for each gate
- Dark terminal-style UI optimised for readability

 Tech Stack
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Graphics:** Inline SVG (no canvas library)
- **No dependencies — fully offline capable**

## How to Run
1. Clone this repo: `git clone https://github.com/rachitajmera19/logicsim-gate-simulator`
2. Open `index.html` in any browser — works instantly

## Gates Implemented
| Gate | Expression | Description |
|------|-----------|-------------|
| AND  | Y = A · B | High only when all inputs are High |
| OR   | Y = A + B | High when at least one input is High |
| NOT  | Y = Ā     | Inverts the input |
| NAND | Y = A̅·̅B̅  | Universal gate — inverted AND |
| NOR  | Y = A̅+̅B̅  | Universal gate — inverted OR |
| XOR  | Y = A ⊕ B | High when inputs differ |
| XNOR | Y = A ⊙ B | High when inputs are equal |

## Relevance
Built as a supplementary tool for the Digital Electronics & Logic Design course at Mahindra University. Directly applies concepts from ECM coursework in an interactive web format.

## Author
**Rachit Ajmera** — Electronics & Computer Engineering, Mahindra University
- LinkedIn: [linkedin.com/in/rachit-ajmera-4457b0243](https://linkedin.com/in/rachit-ajmera-4457b0243)
- GitHub: [github.com/rachitajmera19](https://github.com/rachitajmera19)
