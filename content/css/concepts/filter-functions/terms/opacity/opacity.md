---
Title: "opacity()"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Images"
  - "Functions"
  - "Colors"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-css"
  - "https://www.codecademy.com/learn/paths/front-end-engineer-career-path"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition

Controls how much of the background is visible through the element it is applied to.

## Syntax

```css
filter: opacity(<value>);
```

where a required `<value>` can be one of the following:

- Number value: `0`, `1`
- Percentage value: `25%`, `50%`

**Note:** Value defaults to `1` or `100%` leaving element unchanged. A value of `0` and `0%` will be completely transparent. Negative values as well as values greater than `1` or `100%` are not allowed.

## Example 1
 
Set the opacity of our element to `50%`:

```css
.banner-image {
  filter: opacity(50%);
}
```

