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
const foo = {};
foo.bar = function() {
 return true;
}
```

> All supported languages/abbreviations for syntax highlighting in Linguist's [languages.yml](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml) 

## Create a TODO with a Checklist

- [X] Do a thing
- [ ] Do another thing

```markdown
[X] - Do a thing
[ ] - Do another thing
```

## Link to Issues/Pull Requests

Just reference an issue or PR number in the comment of an issue, PR, or commit!

- Example: **Fixes issue #1**

> You can also `@`-mention a user or org, and use a full or shortened commit SHA-1 hash to automatically link to a commit

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

## Use emoji syntax

:+1: :smile: :trophy: :100: :rocket:

```
:+1: :smile: :trophy: :100: :rocket:
```

## Add a badge

![100% Awesome](https://img.shields.io/badge/Awesome-100%25-brightgreen.svg)

```
![100% Awesome](https://img.shields.io/badge/Awesome-100%25-brightgreen.svg)
```

Build your own at [shields.io](https://shields.io/#/)

## Ignore Markdown Formatting

This is *so cool*  
This is \*so cool\*

```
This is *so cool*
This is \*so cool\*
```

## Things You Can't Do

- Execute JavaScript (via `<script>` tags or otherwise)
