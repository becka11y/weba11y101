---?color=#36173A

## Alt Text

Note: What is it?  
brief description
Why is it important?
- screen reader users
- low bandwidth, images turned off

---
@snap[north span-80]
## Is it Decorative?
@snapend

@snap[west span-50 text-right]
Today's weather: Sunny!
@snapend
@snap[east span-50 text-left]
![](common/techniques/alt-text/img/sun-157126.svg)
@snapend
@snap[south-east text-purple fragment]
It needs empty alt text
@snapend

---
@snap[north span-80]
## Does it Convey Meaning?
@snapend

@snap[west span-50 text-right]
Today's weather:
@snapend
@snap[east span-40 text-left]
![sunny](common/techniques/alt-text/img/sun-147426.svg)
@snapend
@snap[south-east text-purple fragment]
It needs alt text
@snapend

---
@snap[north span-80]
## Does it Contain Text?
@snapend

![You Win!](common/techniques/alt-text/img/youWin.png)
@snap[south-east text-purple fragment]
It needs alt text
@snapend
Note: briefly discuss images of text
---
@snap[north span-80]
## Is it Described in Text?
@snapend

@snap[west span-60 text-08]
The American Robin is a large (10”) bird with a prominent rust orange colored breast and belly. The upper body is grey with a black head. The Robin has a broken white eye ring and has white at the base of the belly before the tail.
@snapend
@snap[east span-40]
![](common/techniques/alt-text/img/robin.jpg)
@snapend
@snap[south-east text-purple fragment]
It may not require alt text
@snapend
Note: could just add robin as alt text - that way SR user knows there is an image with the text. This would also help people with cognitive impairments who use SR
---
@snap[north span-80]
## Alt Text Discussion
@snapend
@snap[midpoint span-80]
![electricity provider home page, has girl spinning on a front lawn](common/techniques/alt-text/img/SCE-home.png)
@snapend

@snap[south-east text-right]
[W3C Alt Text decision tree](https://www.w3.org/WAI/tutorials/images/decision-tree/)
@snapend

---

@snap[north span-80]
## Add via Code
@snapend

@snap[west span-100]
``` html zoom-15 code-wrap
  < img src="https://mysite/files/2018-08/Hero_image.jpg" alt="brief description">
```
@snapend
Note: DON'T use placeholder text - it never gets fixed!

---
@snap[north span-80]
## Add Empty Via Code
@snapend

@snap[west span-100]
```html zoom-15 code-wrap
 < img src="https://mysite/files/2018-08/Hero_image.jpg" alt>
```
@snapend

@snap[south-west span-100]
```html zoom-15 code-wrap
 < img src="https://mysite/files/2018-08/Hero_image.jpg" alt="">
```

@snapend
---
@snap[north span-80]
## Add within CMS
@snapend

@snap[midpoint span-80]
![screenshot of Wordpress image upload](common/techniques/alt-text/img/add-alt-wp.png)
@snapend

@snap[south-west span-100]
Add when upload image or directly edit the code
@snapend

