---?color=#36173A
## Semantic HTML

---
@snap[north span-80]
## Use the correct element
@snapend

@snap[west span-30 fragment]
Links
[go somewhere](https://knowbility.org)
@snapend

@snap[midpoint span-30 fragment]
@box[bg-purple text-white rounded](Buttons)
do something
@snapend

@snap[east span-30 fragment text-05]
@table[table-header custom-row custom-header](common/techniques/semantic-html/table-use.csv)
@snapend

---
@snap[north span-80]
## Use heading elements
@snapend

@snap[west span-70]
```html
<div class="bigH">Bad Heading</div>

<div class="bigH" role="heading”
aria-level=“2”>Acceptable Heading
     
<h1>Correct Topic heading</h1>
```@snapend

@snap[east span-10 fragment]
@color[red](NO!)
@color[gold](Passable)
@color[green](Best)
@snapend

---
@snap[north span-80]
## Headings List
@snapend

@snap[midpoint]
![list of headings in VoiceOver](common/techniques/semantic-html/img/headingsListExVO.png)
@snapend



---
@snap[north span-80]
## Avoid div soup
@snapend


@snap[midpoint span-75]
![alphabet tomato soup with code spelled out in pasta letters](common/techniques/semantic-html/img/soup-751623_640.jpg)
@snapend

---
@snap[north span-90]
## Sectioning Elements and Landmarks
@snapend

@ul[](false)
- main
- nav
- section
- aside
- article
- footer
@ulend

@snap[south-east span-70]
[W3C Sectioning Elements](https://www.w3.org/TR/wai-aria-practices/examples/landmarks/HTML5.html)
@snapend

---
@snap[north span-80]
## Sectioning Element Outline
@snapend


@snap[midpoint span-60]
![block diagram of sectioning elements laid out on a page](common/techniques/semantic-html/img/landmarks.png)
@snapend

---
@snap[north span-90]
## Sectioning "Rules"
@snapend


@ul[text-08](false)
- Generally only 1 main
  - skip link goes to main element
- If more than one landmark of same type provide a label
  - @color[#397193](aria-label="landmark name")
  - @color[#397193](aria-labelledby="id of visual name element")
- Sections should be labeled
- An article should be capable of publishing on its own
@ulend

---?color=linear-gradient(90deg, white 50%, #36173A 50%)
@snap[west span-50]
## Validate your Code!
@snapend

@snap[east span-50]
<a target="_blank" href="https://validator.w3.org/">
![W3C HTML Checker](common/techniques/semantic-html/img/411-html-checker.png)
</a>
@snapend
Note:
discuss why parsing is important (and when it may not be ie. dojo)
 https://w3c.org/wai as a good example
https://bbbs.org only has a few errors

