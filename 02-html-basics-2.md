# 📘 HTML Notes – Text Formatting Tags

---

## 1. `<mark>` Tag

```html
<p>This is <mark>important</mark></p>
```

👉 Highlights text (yellow by default)

---

## 2. `<del>` Tag

```html
<p>This is <del>wrong</del></p>
```

👉 Shows **deleted text** (strikethrough)

---

## 3. `<ins>` Tag

```html
<p>This is <ins>added</ins></p>
```

👉 Shows **inserted text** (underlined)

---

## 4. `<sup>` Tag

```html
<p>2<sup>2</sup> = 4</p>
```

👉 Superscript (power)

---

## 5. `<sub>` Tag

```html
<p>H<sub>2</sub>O</p>
```

👉 Subscript (chemical formulas)

---

## 6. `<q>` Tag (Inline Quote)

```html
<p><q>Hello World</q></p>
```

👉 Adds quotation marks automatically

---

## 7. `<blockquote>` (Extra Tip 🔥)

```html
<blockquote>This is a long quote</blockquote>
```

👉 Used for large quotes

---

## 8. `<abbr>` Tag

```html
<p><abbr title="World Health Organization">WHO</abbr></p>
```

👉 Shows full form on hover

---

## 9. Comments

```html
<!-- This is a comment -->
```

👉 Not visible in browser

---

# 📘 HTML Notes – Anchor Tag Attributes

---

## 1. Target Attribute

```html
<a href="https://example.com" target="_blank">Open</a>
```

### 🔹 Values:

* `_blank` → Opens in new tab
* `_self` → Opens in same tab (default)
* `_parent` → Opens in parent frame

---

## 2. Image as Link

```html
<a href="https://example.com">
    <img src="image.jpg" alt="image">
</a>
```

👉 Clicking image acts like a link

---

## 3. Mail Link

```html
<a href="mailto:example@gmail.com">Send Mail</a>
```

👉 Opens email client to send mail

---

# 📘 HTML Notes – Favicon (Very Important 🔥)

---

## What is Favicon?

👉 Small icon shown in browser tab

---

## How to Add Favicon

```html
<head>
    <link rel="icon" type="image/png" href="favicon.png">
</head>
```

---

## 💡 Best Practices

* Keep favicon in root folder
* Use `.ico` or `.png`
* Size: 16x16 or 32x32

---

# 🔥 Final Summary

* Formatting tags → Used to modify text meaning
* Anchor attributes → Control link behavior
* Favicon → Improves website identity

