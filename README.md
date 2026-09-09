# Self-Development Courseware Package

An interactive, self-contained courseware package on theories of self-development targeted at Semester 3 college students studying Sociology and Psychology.

---

## Deliverables Included

This repository contains four standalone deliverables constructed from the core textbook reading on psychological and sociological theories of self-development:

1. **`index.html`** — A 100% standalone single-page web app.
   - **Zero external dependencies**: All CSS styling, JavaScript interactivity, and structured data are embedded directly within the single file.
   - **No web server required**: Designed to function completely offline using the `file://` protocol.
   - **Features**:
     - *Textbook Reading*: Full formatted reading with highlighted key terms and structured learning objectives.
     - *Study Guide & Comparative Matrix*: High-yield summaries, an interactive searchable comparative theorist matrix, and collapsible review essay prompts with model answers.
     - *Interactive Flashcards*: 3D flip-animation flashcards covering 12 key terms with category tags, counter tracking, and keyboard shortcuts (`Space` to flip, `Arrow Keys` to navigate).
     - *Self-Scoring Quiz*: 7 multiple-choice questions with instant feedback, explanations, dynamic progress tracking, and a score summary with retake capabilities.

2. **`textbook_section.docx`** — Formatted Word document containing the complete textbook section styled with modern typography, headers, callouts, and learning objective boxes.

3. **`study_guide.docx`** — Executive study guide Word document featuring section summaries, a styled 5-column comparative theorist matrix table, a key-term glossary, and review essay prompts accompanied by model academic responses.

4. **`quiz_flashcards.json`** — Structured JSON database containing:
   - `learning_objectives`: Detailed learning goals aligned with undergraduate curriculum standards.
   - `flashcards`: 12 key terms, definitions, and categories.
   - `quiz`: 7 multiple-choice questions with answer keys and detailed conceptual explanations.

---

## How to Open `index.html`

To launch and interact with the single-page web application:

1. **Direct Double-Click**:
   - Double-click `index.html` in your file browser (e.g., Windows File Explorer, macOS Finder).
   - It will open immediately in any standard web browser (Chrome, Firefox, Safari, Edge).

2. **Command Line / Browser**:
   - Open your browser and press `Ctrl+O` (or `Cmd+O` on macOS), then select `index.html`.
   - Alternatively, run from terminal:
     - **macOS**: `open index.html`
     - **Linux**: `xdg-open index.html`
     - **Windows**: `start index.html`

No internet connection, local web server (e.g., `http-server` or `python -m http.server`), or package installation is required.

---

## Learning Objectives Covered

- **Differentiate psychological and sociological theories of self-development**: Compare psychological focus on internal mental development (Freud, Erikson, Piaget, Harlow) with sociological focus on outward social interaction and structure (Durkheim, Cooley, Mead).
- **Explain the process of moral development**: Understand Kohlberg's stages (preconventional, conventional, postconventional) and Gilligan's justice vs. care perspectives.
- **Analyze the influence of gender socialization on behavioral expectations**: Evaluate how cultural expectations, media messaging, and institutional practices shape gendered conduct and role expectations.
