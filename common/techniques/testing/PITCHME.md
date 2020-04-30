---?color=#36173A
## Testing for Accessibility

---
@snap[north span-80]
## Testing Strategy
@snapend

@ul
- Use your keyboard!
- Automated testing
- Manual testing
- Test with users with disabilities
@ulend

Note: automated tools only catch about 30% of errors

---
@snap[north span-80]
## Testing Tools
@snapend

@ul[text-08](false)
- Quick tests: [Beyond automatic accessibility testing: 6 things I check on every website I build](https://www.matuzo.at/blog/beyond-automatic-accessibility-testing-6-things-i-check-on-every-website-i-build/)
- [Paul Adams Bookmarklets](http://www.pauljadam.com/bookmarklets/)
- [axe from Deque](https://www.deque.com/axe/)
- [MS Accessibility Insights for Web](https://accessibilityinsights.io/docs/en/web/overview)
- [Landmarks Extension](https://github.com/matatk/landmarks)
- [WebAIM WAVE Extension](https://wave.webaim.org/extension/)
- [Web Developer Chrome extension](https://chrispederick.com/work/web-developer/)
- [Colour Contrast Analiser](https://developer.paciellogroup.com/resources/contrastanalyser/)
@ulend

---
@snap[north span-80]
## Automated Testing 
@snapend

@ul
- Color Contrast
  - WAVE or aXE
- General code issues - aXe
  - page title
  - page language
  - duplicate ids
  - misuse of ARIA
  - proper landmarks
  - missing alt text
@ulend

---?color=#36173A
@snap[north span-80]
## Manual Testing
@snapend


@ul
- Keyboard
  - can I navigate and use the site
  - skip link available and working
  - Tab order - MS A11y Insights
- Visble Focus
  - Force focus bookmarklet
- Headings
  - Web Developer Tools
@ulend

---?color=#36173A
@snap[north span-80]
## Manual Testing Continued
@snapend


@ul
- Repeated Link Text
- Visual form labels
- Non-text contrast
  - [Exploring WCAG 2.1 - 1.4.11 Non-text Contrast](https://knowbility.org/blog/2018/WCAG21-1411Contrast/)
  - Colour Contrast Analiser
- Reflow, Text spacing, browser zoom
- Popup behavior
@ulend

---
@snap[north span-80]
## Screen Reader Testing
@snapend

@ul
- Proper HTML elements used
  - links, buttons, tables
  - are all controls identified
- Repeated Link Text
- Form labels announced
- Expected keyboard behavior
- Proper use of ARIA
  - Tab panels
  - Menu buttons, etc.
- Error handling
@ulend


---?color=#36173A
@snap[north span-80 text-white]
## Questions
@snapend
@snap[midpoint text-50 text-know-orange font-work-sans-medium]
?
@snapend
