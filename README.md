# Characters

A super-duper simple table for character progress.

### What's it for?
I've used it for scenes and stories where multiple characters are interacting, and found that it's quite a neat way of organizing or presenting the order in which the events take place.

### Focused on getting shit done
It's all very basic and very rough.

- Tailwind is imported directly via a CDN
- The design isn't anything to brag about
  - Except for that sticky table header, obviously 👌
- The JS is the simplest you've seen since jQuery.

The excuse? Nope. Let's focus on finalizing that project of yours.

That reminds me... I shouldn't procrastinate by writing a long read me...

### Getting started

Adjust the settings...

```javascript
// Example settings
const settings = {
    amountOfRows: 50,
    textareaHeight: 3,
    title: 'My name is Alice',
    author: 'Alice',
};
```

...add the characters...

```javascript
// Example data
let data = {
    'miles': {header: 'Miles', rows: []},
    'jack': {header: 'Jack', rows: []},
    'maya': {header: 'Maya', rows: []},
    'stephanie': {header: 'Stephanie', rows: []},
};
```

...and voilà!

All changes will be stored to your Local Storage on any input's `blur`.
It's also possible to export the table data as JSON for other uses (or just for safety!).

Wouldn't it be great to export it in some other, usable format?
That'll be for another day.