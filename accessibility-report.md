# Accessibility Report (Task 2.3)

## Tools Used
- Chrome DevTools Lighthouse (Accessibility)
- WAVE Web Accessibility Tool

## Page Audited
- index.html

## Issues Found
1. **Missing/weak alt text on images**
   - Fix: Added descriptive `alt` text to all images.
2. **Heading hierarchy**
   - Fix: Ensured `h1` is used once for the page title, then `h2` for sections, `h3` for subsections.
3. **Non-descriptive link text**
   - Fix: Replaced vague links like “click here” with descriptive text (e.g., “Contact: send a message using my form”).
4. **Missing language attribute**
   - Fix: Added `lang="en"` to the `<html>` tag.
5. **Form labels**
   - Fix: Ensured every input has a linked `<label for="...">` + matching `id`.

## Lighthouse Results
- Accessibility score: **___/100**
- Date tested: **2026-02-24**
- Notes: (any key notes here)

## Screenshots / Evidence (optional)
- Add screenshots of Lighthouse results or WAVE summary if required by your instructor.