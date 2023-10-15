# This is markdown
- [This is markdown](#this-is-markdown)
  - [Standard features](#standard-features)
    - [Paragraphs](#paragraphs)
- [Heading 1](#heading-1)
  - [Heading 2](#heading-2)
    - [Heading 3](#heading-3)
      - [Heading 4](#heading-4)
        - [Heading 5](#heading-5)
          - [Heading 6](#heading-6)
  - [Extended features](#extended-features)
    - [Texts](#texts)
    - [Render code](#render-code)
    - [Links](#links)
    - [Images](#images)
    - [Quotes](#quotes)
    - [Horizontal lines](#horizontal-lines)
    - [Lists](#lists)
      - [Oredered list](#oredered-list)
      - [Unordered list (\*)](#unordered-list-)
      - [Unordered list (-)](#unordered-list--)
      - [Unordered list (+)](#unordered-list--1)
      - [Nested items (tab or 4 spaces)](#nested-items-tab-or-4-spaces)
    - [Github extended features](#github-extended-features)
      - [Tables](#tables)
        - [Left aling](#left-aling)
        - [Right aling](#right-aling)
        - [Center aling](#center-aling)
    - [Check list (task list)](#check-list-task-list)



## Standard features

### Paragraphs

paragraph one

paragraph two with new line (2 spaces at the end)  
new line in paragraph 2

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

This is a **bold** text
This is another __bold__ text (don't use)

This is an *italics* text
This is another _italics_ text (don't use)

This is both ***italics and bold*** text
This is another both ___italics and bold___ text (don't use)

This is mixed tags _**italics and bold**_ text (don't use)
This is mixed tags *__italics and bold__* text (don't use)

## Extended features

### Texts

This is a ~~cossed~~ text
This is another ~cossed~ text (don't use)

This is an ==highlithed== text
This is an <mark>highlithed mark tag</mark> text

This is a ^superscript^ (ex.: x^2^)
This is a <sup>superscript tag</sup> (ex.: x<sup>2</sup>)

This is a ~subscipt~ (ex.: H~2~O)
This is a <sub>subscript tag </sub> (ex.: H<sub>2</sub>O)

Smile emoji :smile:

### Render code

Single lines 
`this is code`
`let x = 0`

Multiple lines
```
const name = "Mario"
console.log("My name is:", name)
```

Identation
```
if(x >0){
    console.log("Positive")
} else{
    console.log("Negative")
}
```

Language detection
```js
// names collection
let names = ["Mario", "Mariarosa"]
// name loop
names.forEach(name =>{
    console.log(`Hi ${name}``)
})
```

### Links
This is [my site](https://mariolazzari.it)
This is my site <https://mariolzzari.it>

### Images
This is ![my logo](https://www.mariolazzari.it/_next/static/media/logo.61b7d0dd.png)

### Quotes
> quoted line 1
> quoted line 2
> quoted line 3
>
>> nested line after a blank one
>>> double nested line
>>>> triple nested line

### Horizontal lines

---
___
***

### Lists

#### Oredered list

1. Item 1
2. Item 2
3. Item 3

#### Unordered list (*)
* Item 1
* Item 2
* Item 3

#### Unordered list (-)
- Item 1
- Item 2
- Item 3

#### Unordered list (+)
+ Item 1
+ Item 2
+ Item 3

#### Nested items (tab or 4 spaces)
* Item 1
  * Subitem 1
* Item 2
* Item 3
  * Subitem 3
    * Sub item 3 details
  
### Github extended features

#### Tables

| Name | age |
| --- | --- |
| Mario | 48 |
| Mariarosa | 47 |

##### Left aling

| Name | age |
| ---  | :--- |
| Mario | 48 |
| Mariarosa | 47 |

##### Right aling

| Name | age |
| ---  | ---: |
| Mario | 48 |
| Mariarosa | 47 |

##### Center aling

| Name | age |
| ---  | :---: |
| Mario | 48 |
| Mariarosa | 47 |

### Check list (task list)

- [ ] unchecked item
- [x] checked item
- [ ] unchecked item
- [X] checked item 