# Markdown Quick Reference Guide

## Bold and Italic

**Bold** text

_Italic_ text

## Hyperlinks

[Google](https://google.com)

## Blockquotes

>"Markdown syntax is quite simple and fun to learn."

## Lists

* Milk
* Eggs
* Chicken
* Bread

1. Crack three eggs over a bowl
2. Pour a gallon of milk into the bowl
3. Rub the chicken vigorously with butter
4. Drop the chicken into the egg-milk bowl

* Tintin Joe
  * A crime reporter
  * Has poofy orange-red hair
  * Friends with the world's most awesome dog puffy
* Rocky
  * A naval captain
  * Has a long beard
  * Loves rum
  * Possibly also scotch?

## Paragraphs

Lorem ipsum is a pseudo-Latin text used in web design, typography, layout, and printing in place of English to emphasise design elements over content. It's also called placeholder (or filler) text. It's a convenient tool for mock-ups.

## Tables

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

### Alignment

| Syntax    | Description | Test Text   |
| :-------- | :---------: | ----------: |
| Header    | Title       | Here's this |
| Paragraph | Text        | And more    |

### Fenced Code Blocks

```
{
  "firstName": "John",
  "lastName": "Doe",
  "age": 25
}
```

### Syntax Highlighting

```json
{
  "firstName": "John",
  "lastName": "Doe",
  "age": 25,
  "school":"MIT"
}
```

### Footnotes

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.  
    `{ my code }`  
    Add as many paragraphs as you like.

## Custom Heading

### My Great Heading {#custom-id}

## Strikethrough

~~The earth is flat.~~ We now know that the earth is round.

### Task Lists

- [x] Write the code
- [ ] Update the repository
- [ ] Contact companies

#### Automatic URL Linking

http://www.example.com

### Disabling Automatic URL Linking

If you don’t want a URL to be automatically linked, you can remove the link by denoting the URL as code with tick marks.

`http://www.example.com`

### Latex

You need to use latex extension for this.
$$ax+b=c$$
