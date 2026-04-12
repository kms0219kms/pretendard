# Webフォントガイド

PretendardをWebフォントとして使用する方法を案内します。

CDNを利用してPretendardを使用することができ、基本的にjsDelivrを推奨します。cdnjsとUNPKGも使用可能です。

> **推奨：** 最も速く効率的な使用のために[可変ダイナミックサブセット](#可変ダイナミックサブセット)を使用してください。

---

## 可変ダイナミックサブセット

⭐ **推奨する方法です。**

可変Weight属性をサポートし、ページに含まれている文字のみを選択的にダウンロードして、最も速く効率的にPretendardを使用できます。使用するfont-familyの名前は`"Pretendard Variable"`です。

#### HTML

```html
<link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.min.css" />
```

<details>

<summary>cdnjsおよびUNPKG</summary>

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

<summary>cdnjsおよびUNPKG</summary>

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

## ダイナミックサブセット

Pretendardは、Webフォントの容量の問題を解決するための方法として、Google Fontsで提供されるNoto Sans JPと同じ方法で動的サブセットを提供します。ページに含まれている文字のみを選択的にダウンロードしてより速くPretendardを表示するには、下記のコードを使用してください。使用するfont-family名は`Pretendard`です。

#### HTML

```html
<link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/static/pretendard-dynamic-subset.min.css" />
```

<details>

<summary>cdnjsおよびUNPKG</summary>

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

<summary>cdnjsおよびUNPKG</summary>

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

## 可変フォント

可変weightプロパティを使用するには、下記のコードを使用してください。使用するfont-family名は`"Pretendard Variable"`です。

#### HTML

```html
<link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable.min.css" />
```

<details>

<summary>cdnjsおよびUNPKG</summary>

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

<summary>cdnjsおよびUNPKG</summary>

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

## 静的フォント

すべての機能を含むPretendardをWebフォントとして使用するには、下記のコードを使用してください。使用するfont-family名は`Pretendard`です。

#### HTML

```html
<link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/static/pretendard.min.css" />
```

<details>

<summary>cdnjsおよびUNPKG</summary>

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

<summary>cdnjsおよびUNPKG</summary>

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

システムにできるだけ合わせたいなら、下記のようなfont-family構成をおすすめします。

```css
font-family: -apple-system, BlinkMacSystemFont, "Apple SD Gothic Neo", "Pretendard Variable", Pretendard, Roboto, "Noto Sans KR", "Segoe UI", "Malgun Gothic", "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", sans-serif;
```

どこでも同じ環境を持ちたければ下記のようなfont-family構成をおすすめします。

```css
font-family: "Pretendard Variable", Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, "Helvetica Neue", "Segoe UI", "Apple SD Gothic Neo", "Noto Sans KR", "Malgun Gothic", "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", sans-serif;
```
