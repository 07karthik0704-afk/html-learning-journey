
# 📘 Lists

---

## 1. Unordered List (ul)

```html id="3o6c3h"
<ul>
    <li>Apple</li>
    <li>Banana</li>
    <li>Mango</li>
</ul>
```

---

## 🧠 Explanation

* `<ul>` → Unordered list (no specific order)
* `<li>` → List item

👉 Displays as **bullet points**

---

## 2. List Style Type (for ul)

```html id="4j8g72"
<ul style="list-style-type: square;">
```

### 🔹 Values:

* `disc` → ● (default)
* `circle` → ○
* `square` → ■
* `none` → no bullets

---

## 3. Ordered List (ol)

```html id="ljg5q3"
<ol>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ol>
```

---

## 🧠 Explanation

* `<ol>` → Ordered list (with order)
* `<li>` → List item

👉 Displays as **numbers by default**

---

## 4. Type Attribute (for ol)

```html id="lq9x4p"
<ol type="A">
```

### 🔹 Values:

* `1` → 1, 2, 3 (default)
* `A` → A, B, C
* `a` → a, b, c
* `I` → I, II, III
* `i` → i, ii, iii

---

## 💡 Extra Tip (Important 🔥)

You can also start from a specific number:

```html id="kkkg2n"
<ol start="5">
```

👉 Starts list from 5

---

## 🔥 Final Understanding

* `ul` → Bullet list
* `ol` → Number/ordered list
* `li` → List item
* `list-style-type` → Style for ul
* `type` → Style for ol

---

## ⚡ Memory Trick

👉 **UL = Unordered (bullets)**
👉 **OL = Ordered (numbers/letters)**

---

# 📘 HTML Notes – `div` and `span`

---

## 1. `<div>` Tag

```html
<div>This is a div</div>
```

---

## 🧠 Explanation

* `<div>` is a **block-level element**
* Takes **full width** of the screen

👉 Starts on a new line automatically

---

## 🔹 Example

```html
<div style="background-color: lightblue;">
    Hello
</div>
<div style="background-color: lightgreen;">
    World
</div>
```

👉 Each `div` appears on a **new line**

---

## 2. `<span>` Tag

```html
<span>This is a span</span>
```

---

## 🧠 Explanation

* `<span>` is an **inline element**
* Takes only **required space**

👉 Does NOT start on a new line

---

## 🔹 Example

```html
<p>
    Hello <span style="color: red;">Karthik</span>
</p>
```

👉 Only "Karthik" gets styled

---

## 3. Key Differences

| Feature    | `<div>`           | `<span>`            |
| ---------- | ----------------- | ------------------- |
| Type       | Block element     | Inline element      |
| Width      | Full width        | Only needed space   |
| Line break | Yes (new line)    | No                  |
| Usage      | Layout / sections | Styling small parts |

---

## 💡 When to Use

* Use `<div>` → For **structure / layout**
* Use `<span>` → For **styling small text parts**

---

# 📘 HTML Notes – `id` and `class`

---

## 1. `id` Attribute

```html
<h1 id="img">Image Section</h1>
```

---

## 🧠 Explanation

* `id` is used to **uniquely identify an element**
* One `id` should be used **only once** in a page

---

## 🔹 Navigation Using `id`

```html
<a href="#img">Go to Image</a>
```

👉 When clicked, it will **navigate (scroll)** to the element with that `id`

---

## 🔹 Example

```html
<h1 id="img">Image Section</h1>

<a href="#img">Go to Image</a>
```

---

## 2. `class` Attribute

```html
<p class="text">Hello</p>
<p class="text">World</p>
```

---

## 🧠 Explanation

* `class` is used to **group multiple elements**
* Can be used **multiple times**

---

## 🔹 Example with Styling

```html
<p class="red">Hello</p>
<p class="red">World</p>
```

👉 Both will have same styling

---

## 3. Key Differences

| Feature     | `id`           | `class`           |
| ----------- | -------------- | ----------------- |
| Usage       | Unique         | Multiple elements |
| Reusability | Only once      | Many times        |
| Purpose     | Identification | Grouping          |

---

