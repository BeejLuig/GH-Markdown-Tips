# GitHub Markdown Tips

Markdown tips and tricks specific to GH READMEs and Issues

## Make a Table of Contents

- [Heading One](#heading-one)
- [Heading Two](#heading-two)
- [Heading Three](#heading-three)

### Heading One

### Heading Two

### Heading Three

```
- [Heading One](#heading-one)
- [Heading Two](#heading-two)
- [Heading Three](#heading-three)

### Heading One

### Heading Two

### Heading Three
```

## Add Syntax Highlighting to Code Examples

```js
const v

## Create a TODO with a Checklist

- [X] Do a thing
- [ ] Do another thing

```markdown
[X] - Do a thing
[ ] - Do another thing
```

## Make a dropdown

<details>
  <summary>
    Never gonna give you up
  </summary>
  Never gonna let you down
</details>

```html
<details>
  <summary>
    Never gonna give you up
  </summary>
  Never gonna let you down
</details>
```

## Show a diff

```diff
const foo = () => {
- return 'bar'
+ return 'foo'
}
```

> You'll have to check the source for this one 😉

## Add a badge

![100% Awesome](https://img.shields.io/badge/Awesome-100%25-brightgreen.svg)

```
![100% Awesome](https://img.shields.io/badge/Awesome-100%25-brightgreen.svg)
```

Build your own at [shields.io](https://shields.io/#/)

## Align Examples to List Items

- Item one
  ```
  Aligned Example
  ```
- Item two 
```
Not aligned (yuck)
```

## Things You Can't Do

Execute JavaScript

<button onclick="window.alert('hello')">Click me</button>

<a>Click me</a>
