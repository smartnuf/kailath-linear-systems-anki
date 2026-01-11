# Kailath – Linear Systems (Anki Deck)

This repository contains an Anki flashcard deck based on  
**T. Kailath, _Linear Systems_ (1980)**.

The deck is designed for **deep conceptual understanding**, not rote memorisation, and is aimed at readers working seriously through Kailath’s text—particularly those interested in realization theory, minimality, structural properties, and connections to passive network synthesis.

---

## Goals of the Deck

- Support **active recall** while reading Kailath chapter-by-chapter
- Emphasise **structure, invariants, and equivalence**, not just formulas
- Explicitly distinguish:
  - representations vs realisations
  - behaviour vs internal structure
- Provide **guardrails** against common conceptual mistakes
- Build forward links to:
  - minimality
  - Smith–McMillan invariants
  - Jacobi / ladder structure
  - positive-real (PR) and passive network synthesis

This is not an exam-prep deck; it is intended as a **long-lived intellectual companion** to the book.

---

## Repository Structure

.
├── decks/
│ ├── Kailath_Linear_Systems_Ch1.tsv
│ ├── Kailath_Linear_Systems_Ch2.tsv
│ └── images/ # (optional, future)
├── build/
│ └── Kailath.apkg # (optional, generated)
├── README.md

- **TSV (tab-delimited)** files are used instead of CSV for maximum Anki compatibility.
- Images (if added later) should be placed in `decks/images/`.

---

## Card Design Philosophy

Each card has up to seven fields:

1. **Front** – the recall prompt  
2. **Back** – the core answer  
3. **Context** – intuition, clarification, or warnings  
4. **Chapter** – Kailath chapter number  
5. **Section** – section reference or thematic grouping  
6. **Tags** – fine-grained classification  
7. **Image** – optional HTML `<img>` reference  

Cards are deliberately **atomic**: one idea per card.

### Special card categories (via tags)

- `danger` – common misconceptions and conceptual traps
- `preview` – forward-looking ideas used later in the book
- `pr-link` – connections to passive networks and PR theory
- `example micro worked` – small, concrete examples (no long derivations)

---

## Current Coverage

- **Chapter 1**  
  Signals, systems, models, abstraction, equivalence

- **Chapter 2**  
  State-space models, linearity, equivalence, structural non-uniqueness  
  Plus:
  - PR / network-synthesis cross-links
  - Minimality & Smith–McMillan previews
  - Jacobi / ladder previews
  - ABQ / energy-structure previews
  - Explicit “danger cards”

Further chapters will be added incrementally.

---

## How to Import into Anki

1. Open Anki
2. Create (or select) a target deck, e.g.  Kailath – Linear Systems::Ch02
3. **File → Import**
4. Select the `.tsv` file
5. Import settings:
- Fields separated by: **Tab**
- Allow HTML in fields: ✔
- Note type: your custom type (or Basic)
6. Map fields in this order: Front | Back | Context | Chapter | Section | Tags | Image

Repeat for each chapter file.

---

## Recommended Anki Usage

- New cards/day: **10–20** (the material is dense)
- Use **subdecks per chapter**
- Use **tags** to:
- suspend `preview` cards until ready
- periodically review `danger` cards
- Treat failed cards as **conceptual signals**, not memory failures

---

## Copyright & Fair Use

This deck:
- Uses **original paraphrasing**
- Avoids verbatim reproduction of the text
- Does not include scanned figures from the book

It is intended for **educational and personal study use** by readers who own or have access to the textbook.

---

## Status

This is a **living project**.  
Expect:
- revisions,
- clarifications,
- expansion into later chapters,
- possible alternative card styles (e.g. cloze).

Contributions, suggestions, and corrections are welcome via issues or pull requests.

---

## Acknowledgement

Primary source:  
T. Kailath, *Linear Systems*, Prentice-Hall, 1980.

All mistakes or interpretive choices in the cards are the responsibility of the deck author, not the original text.
