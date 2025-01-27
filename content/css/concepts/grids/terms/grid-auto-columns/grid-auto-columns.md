---
Title: "grid-auto-columns"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Grids"
  - "Layout"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-css"
  - "https://www.codecademy.com/learn/paths/front-end-engineer-career-path"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition

A property that specifies the default column size(s) for a container.

## Syntax

```css
.grid-container {
  display: grid;
  grid-auto-columns: <col-value>;
}
```

where `<col-value>` can be one of the following:

- Grid keyword: `auto`, `maxcontent`, `minmax()`
- Pixel value: `300px`
- Percent value: `25%`
- Fractional unit value: `1fr`

## Example 1

A container divided into evenly spaced columns with a minimum width of 100 pixels:

```css
.content-a-container {
  display: grid;
  grid-auto-columns: minmax(100px, auto); 
}
```

## Example 2

A container with columns that each constitute 10% of the available width:

```css
.content-b-container {
  display: grid;
  grid-auto-columns: 10%;
}
```
