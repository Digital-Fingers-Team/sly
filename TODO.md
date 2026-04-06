# TODO.md - Implementation Plan for Task

Current Working Directory: c:/Users/os/Downloads/ISEF (1) - Copy

## Task Summary
1. Remove TTS from index.html (none exists) and letter word-building from ALL pages (camera.html, text-to-sign.html).
2. In text to sound.html: Auto-speak "اهلا", "مرحبا", "عماد", "احمد" in Arabic voice on typing (case-insensitive, trim).

## Steps (in order):

### Step 1: ✅ PLAN CREATED - Edit camera.html
- Remove TTS panel/HTML/JS/CSS.
- Remove letter builder section/HTML/JS/CSS.
- Update processRecognition: No speak or word additions.

### Step 2: Edit text-to-sign.html
- Remove arabic-letters-section entirely (HTML + JS).

### Step 3: Edit text to sound.html
- Add input 'input' listener: Check for trigger words → auto speakText(value, force Arabic).

### Step 4: Verify index.html (no changes).

### Step 5: Test all pages in browser.
- camera.html: Gestures only (no TTS/letters).
- text-to-sign.html: Text→PNG only (no letters).
- text to sound.html: Auto-speak triggers.
- Run `start index.html` for demo.

## Progress
- [x] Plan approved & TODO created
- [x] Step 1: camera.html
- [x] Step 2: text-to-sign.html
- [x] Step 3: text to sound.html
- [x] Step 4: Verify
- [ ] Step 5: Test & complete

Next: Edit camera.html (largest changes).

