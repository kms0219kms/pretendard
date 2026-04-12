# Webfont Guide

This guide explains how to use Pretendard as a web font.

You can use Pretendard via CDN. jsDelivr is recommended by default, and cdnjs and UNPKG are also available.

> **Recommended:** Use [Variable dynamic subset](#variable-dynamic-subset) for the fastest and most efficient experience.

---

## Variable dynamic subset

⭐ **This is the recommended method.**

Supports variable weight axis and dynamically downloads only the characters included on the page, providing the fastest and most efficient way to use Pretendard. Provided font-family name is `"Pretendard Variable"`.

#### HTML

```html
<link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.min.css" />
```

<details>

<summary>cdnjs and UNPKG</summary>

###### cdnjs

```html
<link rel="stylesheet" as="style" crossorigin href="https://cdnjs.cloudflare.com/ajax/libs/pretendard/1.3.9/variable/pretendardvariable-dynamic-subset.min.css" />
```

###### UNPKG

```html
<link rel="stylesheet" as="style" crossorigin href="https://unpkg.com/pretendard@1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.css" />
```

</details>

#### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.min.css");
```

<details>

<summary>cdnjs and UNPKG</summary>

###### cdnjs

```css
@import url("https://cdnjs.cloudflare.com/ajax/libs/pretendard/1.3.9/variable/pretendardvariable-dynamic-subset.min.css");
```

###### UNPKG

```css
@import url("https://unpkg.com/pretendard@1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.css");
```

</details>

---

## Dynamic subset

Use the code below to use Pretendard faster by loading only the font-slices required from the page. Provided font-family name is `Pretendard`.

#### HTML

```html
<link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/static/pretendard-dynamic-subset.min.css" />
```

<details>

<summary>cdnjs and UNPKG</summary>

###### cdnjs

```html
<link rel="stylesheet" as="style" crossorigin href="https://cdnjs.cloudflare.com/ajax/libs/pretendard/1.3.9/static/pretendard-dynamic-subset.min.css" />
```

###### UNPKG

```html
<link rel="stylesheet" as="style" crossorigin href="https://unpkg.com/pretendard@1.3.9/dist/web/static/pretendard-dynamic-subset.css" />
```

</details>

#### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/static/pretendard-dynamic-subset.min.css");
```

<details>

<summary>cdnjs and UNPKG</summary>

###### cdnjs

```css
@import url("https://cdnjs.cloudflare.com/ajax/libs/pretendard/1.3.9/static/pretendard-dynamic-subset.min.css");
```

###### UNPKG

```css
@import url("https://unpkg.com/pretendard@1.3.9/dist/web/static/pretendard-dynamic-subset.css");
```

</details>

---

## Variable

Use the code below to use Pretendard with a variable weight axis. Provided font-family name is `"Pretendard Variable"`.

#### HTML

```html
<link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable.min.css" />
```

<details>

<summary>cdnjs and UNPKG</summary>

###### cdnjs

```html
<link rel="stylesheet" as="style" crossorigin href="https://cdnjs.cloudflare.com/ajax/libs/pretendard/1.3.9/variable/pretendardvariable.min.css" />
```

###### UNPKG

```html
<link rel="stylesheet" as="style" crossorigin href="https://unpkg.com/pretendard@1.3.9/dist/web/variable/pretendardvariable.css" />
```

</details>

#### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable.min.css");
```

<details>

<summary>cdnjs and UNPKG</summary>

###### cdnjs

```css
@import url("https://cdnjs.cloudflare.com/ajax/libs/pretendard/1.3.9/variable/pretendardvariable.min.css");
```

###### UNPKG

```css
@import url("https://unpkg.com/pretendard@1.3.9/dist/web/variable/pretendardvariable.css");
```

</details>

---

## Static

Use the code below to use Pretendard as a web font with entire features. Provided font-family name is `Pretendard`.

#### HTML

```html
<link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/static/pretendard.min.css" />
```

<details>

<summary>cdnjs and UNPKG</summary>

###### cdnjs

```html
<link rel="stylesheet" as="style" crossorigin href="https://cdnjs.cloudflare.com/ajax/libs/pretendard/1.3.9/static/pretendard.min.css" />
```

###### UNPKG

```html
<link rel="stylesheet" as="style" crossorigin href="https://unpkg.com/pretendard@1.3.9/dist/web/static/pretendard.css" />
```

</details>

#### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/static/pretendard.min.css");
```

<details>

<summary>cdnjs and UNPKG</summary>

###### cdnjs

```css
@import url("https://cdnjs.cloudflare.com/ajax/libs/pretendard/1.3.9/static/pretendard.min.css");
```

###### UNPKG

```css
@import url("https://unpkg.com/pretendard@1.3.9/dist/web/static/pretendard.css");
```

</details>

---

## font-family

If you want to fit the system-font as much as possible, the following font-family are recommended:

```css
font-family: -apple-system, BlinkMacSystemFont, "Apple SD Gothic Neo", "Pretendard Variable", Pretendard, Roboto, "Noto Sans KR", "Segoe UI", "Malgun Gothic", "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", sans-serif;
```

If you want to provide the same environment anywhere, the following font-family are recommended:

```css
font-family: "Pretendard Variable", Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, "Helvetica Neue", "Segoe UI", "Apple SD Gothic Neo", "Noto Sans KR", "Malgun Gothic", "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", sans-serif;
```
