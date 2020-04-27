---?color=#36173A
@snap[north span-80]
## Design Considerations for Accessibility
@snapend


@ul
- Color (contrast, meaning)
- Structure & hierarchy
- Interactions (states, errors, confirmations)
- Proximity
- Controls for motion (video, animation)
- What else?
@ulend

---
@snap[north span-80]
## Design Review Tips
@snapend

@ul[text-08]
- Use good color contrast.
- Don’t use color alone for meaning.
- Provide visible focus (“outlines”).
- Design bypass blocks (“skip navigation”).
- Ensure visible labels are on all form fields.
- Document and design form error handling.
- Identify Alternative Text
- Think about keyboard controls for interactions.
@ulend

---
@snap[north span-80]
## Color Contrast
@snapend

@snap[west span-35]
![contrast examples, described below](common/designForA11y/img/143-color-contrast-example.png)
@snapend

@snap[south-west vh]
Black (#000000) text on green (#BBE583) background is 14.6:1 - passes at 14px and 24px;
Red (#BF2828) text on yellow (#EAE463) is 4.4:1 - fails at 14px and passes at 24px;
White (#FFFFFF) text on pink (#EA8894) is 2.1:1 - fails at 14px and 24px;
@snapend

@snap[east span-60]
@ul[text-08](false)
- Ratio of 4.5:1
  - text smaller than 24px (18.66px if bold)
- Ratio of 3.0:1
  - text larger than 24px (18.66px if bold)
- Exclusions
  - logos
  - decorative images (of text)
  - inactive controls
@ulend
@snapend

---
@snap[north span-80]
## Poor Contrast Example
@snapend
@snap[south span-80]
<a target="_blank" href="https://www.amplifyatx.org/">
![screen shot of WebAIM contrast evaluation of site](common/designForA11y/img/143-poor-contrast-with-webaim.png)
</a>
@snapend

---
@snap[north span-80]
## Don't Use Color Alone
@snapend
@snap[west span-50]
![block with word receive with two button to the right, one green and another red](common/designForA11y/img/141-use-of-color-bad.png)
@snapend

@snap[east span-50 fragment]
![block with word receive with two button to the right, one green with text correct and another red with text incorrect](common/designForA11y/img/141-use-of-color-fixed.png)
@snapend


---?color=linear-gradient(90deg, white 50%, #36173A 50%)
@snap[west span-40]
## Focus Visible
[try it yourself](https://arcteryx.com/us/en/)
@snapend


@snap[east span-60 text-white text-08]
Inability to navigate site results in:
@ul[](false)
- Dissatisfied / lost customers
- Lost sales
- Higher customer service costs
- Loss of brand respect
@ulend
@snapend

Note:  https://arcteryx.com/us/en/
https://www.wsj.com/ as examples

---
@snap[north span-80]
## Skip to links/Landmarks
@snapend

@snap[midpoint span-100]
![screen shot of large menu at Starbucks.com](common/designForA11y/img/241-starbucks-large-menu.png)
@snapend

---
@snap[north span-80]
## Skip link examples
@snapend

@snap[west span-50]

<a target="_blank" href="https://www.starbucks.com/">
![Starbucks.com home page with skip link visible](common/designForA11y/img/241-skip-nav-large.png)
</a>

@snapend


@snap[east span-50 text-white text-08]
@ul[](false)
- [Skip Links are Important](https://knowbility.org/blog/2019/skip-links/)
- [Skip Links Design Showcase](https://knowbility.org/blog/2019/skip-links-gallery/)
@ulend
@snapend

Note: starbucks screen shot is a link - have attendees try it out or rei.com. Perhaps follow the link to the design showcase.

---?color=linear-gradient(90deg, white 50%, #36173A 50%)
@snap[west span-50]
## Properly labeled fields
@snapend

@snap[east span-50]
![screen shot of properly labeled contact form](common/designForA11y/img/get-in-touch-form.png)
@snapend

@snap[south-west fragment span-50 text-80]
Placeholder text is not enough
@snapend

---?color=linear-gradient(90deg, white 50%, #36173A 50%)
@snap[north-west span-50]
## Good Error Identification
@snapend
@snap[west span-50 text-08]
@ul
- Message close to original focus point @note[important for screen magnification]
- Detailed message near the control @note[also helps for screen magnification]
- Set focus to (first) control with error @note[this may obfuscate the above two - also is not a change of context since user expects that via submission of form]
- Identification of error to AT @note[use aria-live polite so screen reader will announce]
@ulend
@snapend

@snap[east span-50 fragment]
![screen shot showing form with good error identification and suggestion](common/designForA11y/img/333-error-identify-correct-good.png)
@snapend


---
@snap[north span-80]
## 3.3.1 Example
@snapend
@snap[midpoint span-40]
![error identification example](https://www.youtube.com/embed/DVVdYCDDFtE)
@snapend
@snap[south-east span-80 text-06]
[View error identification example on YouTube](https://youtu.be/DVVdYCDDFtE)
@snapend

---

@snap[north span-90]
## What images need alternative text?
@snapend

@snap[south-west span-45]
![Woman reaching out to shake hands](common/designForA11y/img/no-alt-text-needed-image.png)
@snapend

@snap[south-east span-35]
![stylized leaf above headline Paperless Billing easy and secure](common/designForA11y/img/decorative-img.png)
@snapend

Note:
- brief review of alt text (will discuss more in next session)
- designers determine if is decorative, sets a mood, or needs describing

---?color=linear-gradient(90deg, white 50%, #36173A 50%)

@snap[west span-50 text-08]
## All navigation and interaction can be completed using only the keyboard
@snapend

@snap[east span-50]
![fingers typing on a keyboard](common/designForA11y/img/211-fingers_typing.jpg)
@snapend

---

@snap[north span-80]
## Basic Keyboard Navigation
@snapend

@snap[midpoint span-100 text-06]
@table[table-header custom-row custom-header](common/designForA11y/other/keyboard-table.csv)
@snapend

---
@snap[north span-80]
## Keyboard Interactions
@snapend

@snap[west span-30]
![calendar popup example](common/designForA11y/img/412-example-date-widget.png)
@snapend

@snap[east span-25]
![accordion example](common/designForA11y/img/412-example-accordion.png)
@snapend

@snap[south span-50]
![fancy select example](common/designForA11y/img/412-example-fancy-select.png
@snapend
Note:
- discuss datepicker - it can be made keyboard accessible but at minimum provide the date format and let people type it manually
- accordion can be made fully accessible with keyboard support and ARIA - see the authoring practices - expand/collapse
- this select does work with the keyboard and is styled nicely and works with the keyboard
- provide keyboard equivalent for drag and drop

---?color=#36173A
## Other Design Considerations?

Note:
- Consistent navigation 
- Consistent identification of controls
- icons? How to identify - tooltip, include text?

---
@snap[north span-80]
## What a Design Review Checklist?
@snapend

@ul[](false)
- [Accessibility for Teams - Visual Design](https://accessibility.digital.gov/visual-design/getting-started/)
- [Vox Product Accessibility Guidelines](https://accessibility.voxmedia.com/)
@ulend

---?color=#36173A
@snap[north span-80 text-white]
## Questions
@snapend
@snap[midpoint text-50 text-know-orange font-work-sans-medium]
?
@snapend

