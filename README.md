# GCSE Anki Flashcards

A comprehensive collection of Anki flashcards for GCSE revision, covering multiple subjects and exam boards. These flashcards are designed to help students prepare for their GCSE examinations using spaced repetition.

## Subjects Covered

| Subject | Exam Board | Files | Topics |
|---------|------------|-------|--------|
| **Biology (Triple)** | OCR | 12 | B1-B6: Cell Systems, Scaling Up, Organism Systems, Community Systems, Genetics, Global Challenges |
| **Chemistry (Triple)** | OCR | 25+ | C1-C6: Particles, Elements & Compounds, Chemical Reactions, Predicting Reactions, Monitoring Reactions, Global Challenges |
| **Physics (Triple)** | OCR | 16 | P1-P8: Matter, Forces, Electricity, Magnetism, Waves, Radioactivity, Energy, Global Challenges |
| **Combined Science** | OCR | 52 | Biology, Chemistry, and Physics combined syllabus |
| **Computer Science** | OCR | 12 | Systems Architecture, Storage, Networks, Security, Software, Ethics, Algorithms, Programming |
| **Geography** | AQA | 6 | Natural Hazards, Ecosystems, Tropical Rainforests, Cold Environments, Physical Landscapes, Resource Management |
| **Business** | Edexcel | 10 | Units 1.1-1.5 and 2.1-2.5: Enterprise, Marketing, Operations, Finance, HR |

## Repository Structure

```
gcse-anki-flashcards/
├── Anki decks APKG/                    # Pre-compiled Anki packages (ready to import)
├── GCSE AQA Geography Flashcards/
├── GCSE Edexcel Business Flashcards/
├── GCSE OCR Biology Flashcards/
├── GCSE OCR Chemistry Flashcards/
│   └── PMT Notes C4-6/                 # Additional study notes
├── GCSE OCR Combined Science Flashcards/
│   ├── GCSE OCR Combined Biology Flashcards/
│   ├── GCSE OCR Combined Chemistry Flashcards/
│   └── GCSE OCR Combined Physics Flashcards/
├── GCSE OCR Computer Science Flashcards/
├── GCSE OCR Physics Flashcards/
└── README.md
```

## Flashcard Format

All text-based flashcards use the **pipe character (`|`)** as a delimiter for Anki import:

```
Question | Answer
```

Each file contains flashcards in two styles:
- **Definitions (`_defs`)** - Key term definitions
- **Notes (`_notes`)** - Detailed concept explanations

## How to Import

### Method 1: Import Text Files

1. Open **Anki Desktop** application
2. Go to `File` → `Import`
3. Select the `.txt` flashcard file
4. Set the field separator to **Pipe (`|`)**
5. Choose your target deck and import

### Method 2: Import APKG Files (Recommended)

1. Open **Anki Desktop** application
2. Go to `File` → `Import`
3. Select the `.apkg` file from the `Anki decks APKG/` folder
4. The deck will be imported with all flashcards included

Available APKG decks:
- GCSE AQA Geography
- GCSE Edexcel Business
- GCSE OCR Biology
- GCSE OCR Chemistry
- GCSE OCR Physics
- GCSE OCR Combined Biology
- GCSE OCR Combined Chemistry
- GCSE OCR Combined Physics
- GCSE OCR Computer Science

## Recommended Anki Settings

Enable **FSRS (Free Spaced Repetition Scheduler)** in Anki options for optimal learning:

- An advanced scheduling algorithm that adapts to your memory patterns
- Provides more personalized and efficient learning by adjusting review intervals
- Improves retention compared to the older SM-2 algorithm
- Adjusts intervals based on how well you remember the material

To enable: `Tools` → `Preferences` → `Scheduling` → Enable FSRS

## How These Flashcards Were Created

These flashcards were generated using Claude AI with custom prompts designed for educational content:

| Content | Model | Prompt |
|---------|-------|--------|
| **Triple Sciences** (Biology, Chemistry, Physics) | Claude Sonnet 4 | [`anki-flashcard/prompt-v2.txt`](https://github.com/maaarcooo/llm-custom-instructions/blob/main/anki-flashcard/prompt-v2.txt) |
| **Combined Science** | Claude Sonnet 4.5 | [`anki-flashcard/prompt-v3.txt`](https://github.com/maaarcooo/llm-custom-instructions/blob/main/anki-flashcard/prompt-v3.txt) |

## License

This project is licensed under the Creative Commons Attribution 4.0 International License - see the [LICENSE](LICENSE) file for details.

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose

Under the following terms:
- **Attribution** — You must give appropriate credit and indicate if changes were made

## Credits

- Flashcard content generated with [Claude](https://claude.ai) by Anthropic
- Based on OCR, AQA, and Edexcel GCSE specifications
- Anki spaced repetition software: [apps.ankiweb.net](https://apps.ankiweb.net)
