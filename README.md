![header](https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=capsule%20render&fontSize=90)
<p align='center'> Decorate GitHub Profile or any Repo like me! </p>
<p align='center'>
  <a href="https://github.com/kyechan99/capsule-render/labels/Idea">
    <img src="https://img.shields.io/badge/IDEA%20ISSUE%20-%23F7DF1E.svg?&style=for-the-badge&&logoColor=white"/>
  </a>
  <a href="#demo">
    <img src="https://img.shields.io/badge/DEMO%20-%234FC08D.svg?&style=for-the-badge&&logoColor=white"/>
  </a>
</p>

## Types
- [wave](#wave)
- [egg](#egg)
- [shark](#shark)
- [slice](#slice)
- [rect](#rect)

Any of Idea -> [Idea-Issue](https://github.com/kyechan99/capsule-render/labels/Idea) or [PR](https://github.com/kyechan99/capsule-render/pulls)

# How to Use
```
https://capsule-render.vercel.app/api?
```
Just write query parameter end of this url. Like this

Markdown:
```
![header](https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=capsule%20render&fontSize=90)
```

HTML:
```
<img src="https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=capsule%20render&fontSize=90" />
```

## Type
Type data makes to change Background Image.
- [wave](#wave) : default
- [egg](#egg)
- [shark](#shark)
- [slice](#slice)
- [rect](#rect)

Write `&type= ` on the URL
```
![header](https://capsule-render.vercel.app/api?type=slice)
```

## Color
Change Background Image!
- `&color=auto` : Proven random color. List are [here](https://github.com/kyechan99/capsule-render/blob/master/src/pallete.json)
- `&color=timeAuto` : Proven random color, but is decided by time.
- `&color=random` : Really random color. I don't know what colors are showing.
- `&color=gradient` : Proven random gradient. List are [here](https://github.com/kyechan99/capsule-render/blob/master/src/gradient.json)
- `&color=timeGradient` : Proven random gradient, but is decided by time.
- `&color=_hexcode` : default(#B897FF)

If you use `auto` mode. no need to change `fontColor`. 
`auto` also change fontColor auto.

```
![header](https://capsule-render.vercel.app/api?color=auto)
```
> If you use static color. Do not write '#'

> When use `timeAuto` and `timeGradient`?
>
> Used section `header` and `footer` at the same time. 

## Section
Section data makes reverse Background Image.
- `&section=header` : (default)
- `&section=footer`

Write `&section= ` on the URL
```
![footer](https://capsule-render.vercel.app/api?section=footer)
```

## Height
Change Image Size. Default value is 200.

Write `&height= ` on the URL
```
![header](https://capsule-render.vercel.app/api?height=400)
```
> Do not write `px`

## Text
Input text over the Image.

Write Something `&text= `.

```
![header](https://capsule-render.vercel.app/api?text=Hello%World!)
```

> You can't use some Special Characters. Like '#', '&', '/' ... 
>
> It makes confused API

## FontColor
Change text color. Default value is 000000
Value should be Hex code with erased '#'

Write `&fontAlign= ` behind **Text** query

```
![header](https://capsule-render.vercel.app/api?text=Hello%World!&fontColor=d6ace6)
```

## FontSize
Change text font size. Default value is 80.

Write `&fontSize= ` behind **Text** query

```
![header](https://capsule-render.vercel.app/api?text=Hello%World!&fontSize=40)
```

> Do not write `px`

## FontAlign
Change text align. write number **between 0~100**

`&fontAlign= ` : Default value is 50. center of image

```
![header](https://capsule-render.vercel.app/api?text=Hello%World!&fontAlign=70)
```


# Demo <a id="demo">

## Wave <a id="wave">
![wave](https://capsule-render.vercel.app/api?type=wave&color=auto&height=200&text=WAVE)

## Egg <a id="egg">
![egg](https://capsule-render.vercel.app/api?type=egg&color=auto&height=210)

## Egg <a id="shark">
![egg](https://capsule-render.vercel.app/api?type=shark&color=gradient&height=140)

## Slice <a id="slice">
![slice](https://capsule-render.vercel.app/api?type=slice&color=auto&height=200&text=SLICE&fontAlign=82)
  
## Rect <a id="rect">
![rect](https://capsule-render.vercel.app/api?type=rect&color=gradient&text=RECT&fontAlign=30&fontSize=30)


<hr/>

# Things that helped contribute

- SVG Path Easy Maker [Codepen](https://codepen.io/kyechan99/pen/yLeQVBa)
- SVG Path draw [mavo.io](https://mavo.io/demos/svgpath/)


![footer](https://capsule-render.vercel.app/api?type=wave&color=auto&height=200&section=footer&text=Now%20Use%20me!&fontSize=90)
