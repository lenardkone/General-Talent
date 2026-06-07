# Design Review

Review the current UI/HTML/CSS for design quality. Check:

## Visual Design
- [ ] Consistent spacing (are margins/paddings using a scale?)
- [ ] Typography hierarchy (headings, body, captions — clear size contrast?)
- [ ] Color usage (too many colors? sufficient contrast?)
- [ ] Alignment (elements aligned to a grid?)

## UX & Usability
- [ ] Clear call-to-action (is the primary action obvious?)
- [ ] Empty states handled
- [ ] Loading/error states considered
- [ ] Mobile layout works (not just desktop)

## Accessibility
- [ ] Color contrast ≥ 4.5:1 for body text, ≥ 3:1 for large text
- [ ] Interactive elements have focus styles
- [ ] Images have alt text
- [ ] Form inputs have labels

## Code Quality
- [ ] No magic pixel values (use consistent spacing tokens)
- [ ] No inline styles that should be classes
- [ ] CSS is organized and not redundant

For each issue found: describe the problem, explain why it matters, and provide a concrete fix.

$ARGUMENTS
