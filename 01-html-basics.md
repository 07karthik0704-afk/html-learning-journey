# 🌐 HTML Notes & Basics

---

## 🧠 What is HTML?

**HTML** = *Hyper Text Markup Language*

### 🔹 Breakdown:

* **HyperText** → Links between pages
* **Markup** → Tags to structure content
* **Language** → Builds web page structure

👉 HTML defines the **structure**, not design or logic.

---

## ⚙️ Web Development Basics

| Technology | Purpose   |
| ---------- | --------- |
| HTML       | Structure |
| CSS        | Styling   |
| JavaScript | Logic     |

---

## 🏷️ Tags & Elements

* Opening Tag → `<h1>`
* Closing Tag → `</h1>`
* Element → `<h1>Hello</h1>`

👉 Everything in HTML is made of **elements**.

---

## 🧱 Basic HTML Structure

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Portfolio</title>
  </head>
  <body>
    <h1>Hello World</h1>
  </body>
</html>
```

---

## 💬 Comments

```html
<!-- This is a comment -->
```

✔️ Not visible in browser

---

## 📜 History

* 1989 → WWW invented (Tim Berners-Lee)
* 1991 → HTML introduced
* 2014 → HTML5 released

---

## 🌍 How Browser Works

* Reads HTML
* Understands structure
* Displays content inside `<body>`

---

## 🛠️ Developer Tools

* View Page Source
* Inspect (DevTools)

---

## 🔠 Headings

```html
<h1> to <h6>
```

* `<h1>` → Most important
* `<h6>` → Least important

⚠️ Use for **SEO**, not styling

---

## 📄 Paragraph

```html
<p>This is a paragraph</p>
```

---

## 📌 Preformatted Text

```html
<pre>
  Hello
    World
</pre>
```

---

## 🔗 Anchor (Links)

```html
<a href="https://example.com">Click Here</a>
```

---

## 🖼️ Image

```html
<img src="image.jpg" alt="image" width="200">
```

### Attributes:

* `src`
* `alt`
* `width`, `height`

---

## ➖ Line & Break

```html
<hr>
<br>
```

---

## 🌐 URLs

* Absolute → `https://...`
* Relative → local path

---

## 🔤 Case Sensitivity

✔️ HTML is not case-sensitive
👉 Use lowercase (best practice)

---

# 🎨 HTML Style Attribute

---

## 📌 What is `style` Attribute?

* `style` is an **HTML attribute**
* Used to apply **CSS directly inside HTML elements**

👉 It allows you to add styling **inline** within HTML.

---

## ⚙️ Syntax

```html
<tag style="property: value;">
```

---

## 🧪 Example

```html
<p style="color: green;">Hello World</p>
```

---

## 🔍 Understanding

> `style` is an attribute, `color` is a property, and `green` is a value

---

## 🧩 Multiple Properties

```html
<p style="color: red; font-size: 20px;">
```

* Use **semicolon (`;`)** to separate properties

---

## 🎯 Common Properties

* `color` → Text color
* `background-color` → Background color
* `font-size` → Text size
* `text-align` → Alignment
* `border` → Border styling
* `font-family` → Font style

---

## ⚠️ Important Notes

* This is called **Inline CSS**
* HTML → Structure
* CSS → Styling
* `style` attribute allows CSS inside HTML

---

## 💡 Best Practices (Styling)

* ❌ Avoid too much inline CSS
* ✅ Prefer **external CSS**
* ✅ Use inline CSS only for quick testing

---

## 🚀 Pro Tip

Inline CSS is useful for:

* Quick debugging
* Testing styles
* Small one-time changes

👉 For real projects → use **external `.css` files**

---

## 📏 Units

* `px` → Fixed
* `%` → Relative

---

## 🧷 Tooltip

```html
<p title="Tooltip text">Hover me</p>
```

---

## ✍️ Text Formatting

### Bold

```html
<b>Bold</b>
<strong>Important</strong>
```

### Italic

```html
<i>Italic</i>
<em>Emphasized</em>
```

### Small

```html
<small>Text</small>
```

---

## 💡 Best Practices

* ✅ Write clean code
* ✅ Use proper indentation
* ✅ Prefer semantic tags
* ✅ Think SEO

> "Can a search engine understand my page?" 🤔

---

# 📘 HTML Notes – Quotes Inside Quotes

---

## ❓ Problem

If you write like this ❌

```html id="6p3w7g"
<p title="He said "Hello"">Text</p>
```

👉 This breaks because HTML gets confused with nested double quotes.

---

## ✅ Solution

### 👉 Use Single Quotes Inside

```html id="q3c5lw"
<p title="He said 'Hello'">Text</p>
```

✔ Works perfectly

---

## 🔄 Alternative Way

### 👉 Use Single Quotes Outside & Double Inside

```html id="h6h6ju"
<p title='He said "Hello"'>Text</p>
```

✔ Also correct

---

## 🧠 Rule to Remember

* Double quotes outside → Use single quotes inside
* OR
* Single quotes outside → Use double quotes inside

---

## 💡 Pro Tip (Advanced)

You can also use **HTML Entities**:

```html id="f4w3hz"
<p title="He said &quot;Hello&quot;">Text</p>
```

👉 `&quot;` = `"`

---

## 🔥 Final Understanding

> Never use the same type of quotes inside the same quotes directly — it will break the HTML

---

## 🏷️ HTML Element Explanation

```html
<h1>Hello</h1>
```

### 🔍 Breakdown:

* `<h1>` → Opening tag
* `</h1>` → Closing tag
* `Hello` → Content (Text Content)

---

### 💡 Final Understanding

An HTML element consists of:

* Opening tag
* Content
* Closing tag

👉 Together, they form a complete **HTML element**

---
