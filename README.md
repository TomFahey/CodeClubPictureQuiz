# Picture Quiz — M5Stack Tab5 Coding Lesson

A block-based coding lesson for ages 9–13 that teaches students how to build a multi-round picture quiz game on the M5Stack Tab5 using UIFlow2.

## About the Project

This repository contains a complete, student-ready coding lesson created through the UIFlow2 Lesson Maker pipeline:

- **`program-design.md`** — Technical program design (block layout, widget positions, data structures, event flow)
- **`lesson-plan.md`** — Student-friendly lesson plan with analogies, diagrams, pedagogical review, and step-by-step build instructions
- **`index.html`** through **`lesson-step-7.html`** — Beautiful learner-facing HTML lesson pages with CSS-styled blocks, sidebar navigation, and progress tracking

## What Students Build

A **Picture Quiz** game with 8 rounds featuring:

- 🎬 A title screen with a START button
- 🎮 A game screen showing a picture and four answer choices
- 🏆 A game-over screen with final score and persistent high score
- 📦 Quiz data stored in lists (images, answers, correct indices)
- 💾 High score saved via NVS (non-volatile storage) so it survives power-offs

## Concepts Covered

- Variables, Lists (including list-of-lists), Functions, Event Handling, Conditional Logic, Page Navigation, NVS

## Hardware Requirements

- M5Stack Tab5 controller
- USB connection
- 8 quiz images (256×256 JPG) uploaded to `/flash/res/img/`

## Lesson Structure

| Step | File | Topic |
|------|------|-------|
| 1 | `index.html` | Create project + design 3 screens in UI Editor |
| 2 | `lesson-step-2.html` | Variables and quiz data lists |
| 3 | `lesson-step-3.html` | `setup_round()` function |
| 4 | `lesson-step-4.html` | `check_answer()` function |
| 5 | `lesson-step-5.html` | `show_gameover()` function |
| 6 | `lesson-step-6.html` | Wire up buttons and play |
| 7 | `lesson-step-7.html` | NVS — persistent high score |

## Built With

- [UIFlow2](https://uiflow2.m5stack.com/) — M5Stack's visual block programming platform
- UIFlow2 Lesson Maker agents — automated lesson design and publishing pipeline
