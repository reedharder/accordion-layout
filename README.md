# C♯/D button accordion trainer

An interactive chart and spaced-repetition flashcards for memorizing the layout of a 23-button C♯/D button accordion with the modern 8-button bass layout.

**Open it:** https://reedharder.github.io/accordion-layout/

## Keyboard

The full layout, drawn the way the chart shows it: left half of each button is push, right half is pull.

- Press and hold any half to hear it (synthesized reed tone; bass buttons play root + octave, chord buttons play a major triad).
- **Bellows: Push / Pull** dims the other direction, and either half of a button then plays that direction, as on the real box.
- **Find a note** lights every place a note sits.
- **Hide note names** blanks the chart so you can quiz yourself; pressing a button peeks at it.

## Flashcards

Five decks, meant to be learned in order. Each deck is one row and one bellows direction, so you learn a single repeating pattern at a time:

1. D row, push: D – F♯ – A
2. D row, pull: G – B – C♯ – E
3. C♯ row, push: C♯ – F – G♯
4. C♯ row, pull: F♯ – A♯ – C – D♯
5. Bass side, push and pull (each chord button is the major chord of the bass button to its right)

Two card types, which you can toggle:

- **Name the note:** one button is highlighted on a blank chart with a direction; say the note, then reveal (it plays the tone).
- **Find the button:** a note and direction are given; tap the button. It's graded on the spot, and any button that plays the note counts, since the rows repeat.

Grading is Again / Hard / Good / Easy with Anki-style intervals. Progress is stored in your browser's localStorage.

## Notes

Note names come from the "23 button C#/D modern bass layout" chart. Octaves are a guess: each treble row is assumed to rise left to right from C♯3 / D3, so the pitches are only approximate.

Everything is in `index.html`, with no build step.
