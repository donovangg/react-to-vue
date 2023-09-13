---
title: Using Curly Braces and JS Expressions
description: How React uses curly braces and Vue's Mustache
---

Guides lead a user through a specific task they want to accomplish, often with a sequence of steps.
Writing a good guide requires thinking about what your users are trying to do.

## How Vue and React use curly braces.
Both Vue and React use some sort of <code>{}</code> curly brace syntax. They both also have
similar use cases in that inside of your curly braces, you can write valid JavaScript in your framework.

React
```javascript
let name = 'Lebron';

<p>Hi {name}!!</p>
```

The difference in Vue is that it uses it's own syntax that it refers to as mustache syntax.
```javascript
let name = 'D Wade'

<p>Yo {{name}} I'm open!</p>
```

## Further reading

- Read [about how-to guides](https://diataxis.fr/how-to-guides/) in the Diátaxis framework
