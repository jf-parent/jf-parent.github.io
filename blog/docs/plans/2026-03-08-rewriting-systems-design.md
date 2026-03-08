# Rewriting Systems Article Design

## Format
- Org-mode blog post
- Dense but punchy (~3000-4000 words)
- Tone: neutral but sharp, declarative, no exclamation marks
- Code blocks: Clojure as connective tissue, Maude/Wolfram/Python where authentic
- Visuals: ASCII/text-based for now (placeholders for future images/GIFs)

## Structure

### Opening (no header)
- Cold open: "Every program you've ever written is a rewriting system."
- 3-line Clojure snippet reframed as a rewrite rule
- Promise paragraph establishing escalation without naming the three acts

### Act I: Rewriting Is Computation
1. **Peano axioms** — arithmetic as rewrite rules
   - `S(S(0)) + S(0)` reducing step by step (ASCII)
   - Clojure implementation
2. **A=B game** — computation as puzzle
   - Recreate one level as ASCII
   - Brief description of the Steam game
3. **Knuth-Bendix** — making rewriting systems work
   - Two overlapping rules, critical pair, resolution
   - ASCII confluence diamond
   - Clojure or pseudocode

### Act II: Everything Is Pattern Matching
1. **Maude** — a language built on rewriting
   - Sorting algorithm as pure rewrite rules (Maude syntax)
   - ASCII reduction steps
2. **Wolfram Language** — pattern matching as paradigm
   - Symbolic differentiation in 3-4 lines
   - Cellular automaton as rewrite rule (ASCII generations)
3. **Church-Rosser** — when order doesn't matter
   - ASCII diamond diagram
   - Twist: most interesting systems are not confluent
   - Connection to lazy vs eager evaluation

### Act III: Simple Rules, Alien Consequences
1. **L-Systems** — one rule, a forest
   - `A -> AB, B -> A` with 7 generations (ASCII)
   - Fibonacci connection reveal
   - ASCII tree/Koch curve
   - Python code block
2. **The edge** — undecidability
   - Word problem is undecidable
   - Knuth-Bendix doesn't always terminate
   - Rule 110 is Turing-complete
   - Brief, sharp, no fat

### Closing
- Quiet reframe: compiler, regex, spreadsheet — all rewriting
- No grand summary

### References/Resources
- EATCS Monographs on Theoretical Computer Science 14
- Baader & Nipkow, *Term Rewriting and All That*
- Dershowitz & Jouannaud, *Rewrite Systems* (Handbook of TCS)
- Prusinkiewicz & Lindenmayer, *The Algorithmic Beauty of Plants*

## Punchlines (per section)
- Peano: "You didn't compute anything. You rewrote symbols until they stopped changing."
- A=B: "Every level is a proof. You just don't notice because it feels like play."
- Knuth-Bendix: "An algorithm that writes its own rules."
- Maude: "No loops. No branches. Just rules firing until nothing matches."
- Wolfram: "Mathematica isn't a calculator. It's a rewriting engine with good marketing."
- Church-Rosser: "Church-Rosser tells you when you can stop worrying. The catch is, you usually can't."
- L-Systems: "One rule. No intelligence. A forest."
- The edge: "The simplest possible rules. The hardest possible questions. That's the deal."
