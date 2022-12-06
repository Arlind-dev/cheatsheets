### Table of contents
[Headers](https://github.com/Arlind-dev/cheatsheets/blob/main/git-bash/markdown.md#headers)
[Character Changes](https://github.com/Arlind-dev/cheatsheets/blob/main/git-bash/markdown.md#character-changes)
[Lists](https://github.com/Arlind-dev/cheatsheets/blob/main/git-bash/markdown.md#lists)
[Links](https://github.com/Arlind-dev/cheatsheets/blob/main/git-bash/markdown.md#links)
[Images](https://github.com/Arlind-dev/cheatsheets/blob/main/git-bash/markdown.md#images)
[Code stuff](https://github.com/Arlind-dev/cheatsheets/blob/main/git-bash/markdown.md#code-stuff)
[Tables](https://github.com/Arlind-dev/cheatsheets/blob/main/git-bash/markdown.md#tables)
[Horizontal lines](https://github.com/Arlind-dev/cheatsheets/blob/main/git-bash/markdown.md#horizontal-lines)
[HTML](https://github.com/Arlind-dev/cheatsheets/blob/main/git-bash/markdown.md#html)
[Quotes](https://github.com/Arlind-dev/cheatsheets/blob/main/git-bash/markdown.md#quotes)
[Footnotes](https://github.com/Arlind-dev/cheatsheets/blob/main/git-bash/markdown.md#footnotes)



### Headers

```
# H1
## H2
### H3
#### H4
##### H5
###### H6

another way to write h1 and h2

H1
===

H2
---

```
# H1
## H2
### H3
#### H4
##### H5
###### H6

another way to write h1 and h2

H1
===

H2
---

### Character Changes

```
this is in *italic*
this is also in _italic_
this is **fat**
this is also __fat__

This is _**fat and italic**_
this is also *__fat and italic__*
(theres probably more combinations above but I'll ignore this)
```
this is in *italic*
this is also in _italic_
this is **fat**
this is also __fat__

This is _**fat and italic**_
this is also *__fat and italic__*
(theres probably more combinations above but I'll ignore this)

### Lists
```
1. list 1
2. List 2
3. List 3
   3.1 Sub list 1
   3.2 Sub list 2

* unordered list
* asdf
- also unordered
- asdf
+ also unordered
+ asdf
```

1. list 1
2. List 2
3. List 3
   3.1 Sub list 1
   3.2 Sub list 2

* unordered list
* asdf
- also unordered
- asdf
+ also unordered
+ asdf

### Links
```
[text it should be shown as / alt text](link to path or website)
example: [not youtube](https://www.google.com/)

Can be used in [texts](https://www.google.com/)
```
example: [not youtube](https://www.google.com/)

Can be used in [texts](https://www.google.com/)

### Images
```
![alt text for image](link to image or path to image)
![alt text](https://cdn.pixabay.com/photo/2016/03/21/23/25/link-1271843_1280.png)
```

![alt text](https://cdn.pixabay.com/photo/2016/03/21/23/25/link-1271843_1280.png)

### Code stuff

```
this is a `blocked text`
```
this is a `blocked text`

````

```
this is a completely blocked text
```

```
this is a completely blocked text
```

```python
print("this is python hopefully)
```

```javascript
console.log("this is javascript hopefully")
```

to block blocked text you start it with four back-ticks instead
````


```
this is a completely blocked text
```

```python
print("this is python hopefully")
```

```javascript
console.log("this is javascript hopefully")
```
to block blocked text you start it with four back-ticks instead

### Tables
```
| tables      | are         | annoying |
|-------------|-------------|----------|
| `that's`    | *why*       | **I*     |
| _**make**_  | them        | in       |
| excel       | and         | export   |
| them        | as          | markdown |
```
| tables      | are         | annoying |
|-------------|-------------|----------|
| `that's`    | *why*       | **I*     |
| _**make**_  | them        | in       |
| excel       | and         | export   |
| them        | as          | markdown |

the `|--------|----------|----------|` makes the lines fat, and are needed to make a working table in markdown

you also dont need to allign them in markdown
```
|tables|are|annoying|
|---|---|---|
|`that's`|*why*|**I*|
|_**make**_|them|in|
|excel|and|export|
|them|as|markdown|
```
|tables|are|annoying|
|---|---|---|
|`that's`|*why*|**I*|
|_**make**_|them|in|
|excel|and|export|
|them|as|markdown|

but if you dont, you're a psychopath

### Horizontal lines
```
---

___

***
```

---

___

***

### HTML

in markdown almost every html syntax is valid

```
this is a normal text <br> but theres a breakpoint
```

this is a normal text <br> but theres a breakpoint

cool I think

### Quotes
```
> this is a quote
> this is still a quote

this is no longer a quote

> quote
```

> this is a quote
> this is still a quote

this is no longer a quote

> quotes

### Footnotes
```
this is a footnote[^1].

this is another footnote[^2].

footnotes dont need to be numbers[^note].

[^1]: because they use the same footnote id / number / word this one gets linked here
[^2]: because they use the same footnote id / number / word this one gets linked here
[^note]:
    because they use the same footnote id / number / word this one gets linked here
but you may have noticed that even though I wrote `[^note]` it still got rendered as a number
```
this is a footnote[^1].

this is another footnote[^2].

footnotes dont need to be numbers[^note].

[^1]: because they use the same footnote id / number / word this one gets linked here
[^2]: because they use the same footnote id / number / word this one gets linked here
[^note]:
    because they use the same footnote id / number / word this one gets linked here
but you may have noticed that even though I wrote `[^note]` it still got rendered as a number
