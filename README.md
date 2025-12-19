# noesis

> *From Greek νόησις — understanding, intellect, direct knowing.*

**noesis** is an experimental programming language and language-definition system focused on **clarity, structure, and meta-level expressiveness**.  
It explores the boundary between *defining a language* and *using one* — treating syntax, semantics, and rules as first-class concepts.

This project is both a **language** and a **research playground**.

---

## Goals

- Minimal but expressive core
- Declarative *and* imperative programming styles
- Strong emphasis on language design, not just implementation
- Human-readable syntax that stays close to formal grammar
- Designed to be easy to reason about, skim, and extend

---

## Philosophy

Most languages hard-code their rules.

**noesis** asks:  
> *What if the rules themselves were programmable?*

The language is built in layers, where higher layers describe lower ones.  
Syntax, operators, and semantics are not magic — they are defined.

This makes noesis ideal for:
- Language experimentation
- Compiler/interpreter research
- Learning how programming languages actually work under the hood

---

## Key Features

- Layered language system (meta → core → user)
- Grammar-driven design (EBNF-inspired)
- Clear separation of syntax, operators, and semantics
- Simple primitives with extensible structures
- Designed to be readable before it is clever

---

## Project Structure

```text
noesis/
├── src/py          # Interpreter source (in Python 3.13)
├── src/c           # Interpreter source (in C)
├── docs/           # Documentation and design notes
├── examples/       # Example programs
├── grammar/        # Grammar and language definitions
├── docs/licenses/  # License texts
└── README.md
```
