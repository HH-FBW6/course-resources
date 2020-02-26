# Psuedo Classes

---

## Why do we need them?

- Sometimes we want to access an element based on it's state
- Sometimes it's not possible to access an element, because the element is added dynamically

## How do we use them?

We use a colon [`:`] symbol (as opposed to a dot [`.`] symbol for regular classes). For example,to modify the hover state of an element, we use the `:hover` pseudo selector like so:

`button:hover`

## Commonly used psuedo classes

**`:hover`**

Access the hover state of an element

**`:checked`**

For: `<input type="radio">`
For: `<input type="checkbox">`
For: `<option> in a <select>`

Denotes the selection is on

**`:focus`**

An element which has received user focus (for example an input element)

**`:first-child`**

Selects the first child in a group

**`:last-child`**

Selects the last child in a group

## Further reading

[https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes](
https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)