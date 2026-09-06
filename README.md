# Word Tray Trainer

A simple browser-only vocabulary trainer.

## New features

- Saved tray state persists across browser reloads.
- Trays are color coded: green (Know Perfectly), yellow (Know but can forget), red (Repeat Daily).
- Words in a tray can be deleted with two confirmations.
- Export PDF creates an A4 landscape PDF with the three trays in separate columns; words use the tray color.
- Clear All Words offers a backup PDF before the final deletion confirmation.
- The Context Game uses the Repeat Daily tray.

## CSV format

Required: `word`

Recommended: `definition`, `sentence`, `synonyms`

Use `___` in a sentence where possible for the Context Game.

## Use

Open `index.html` in a modern browser. PDF export uses jsPDF from cdnjs, but it can run locally without internet.

Importing a new CSV starts a fresh sorting session. Clear All Words clears the saved vocabulary and tray assignments from this browser.
