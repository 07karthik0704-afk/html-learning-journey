# 📘 HTML Notes – `iframe`

---

## 1. What is `iframe`?

👉 `<iframe>` = **Inline Frame**

* Used to **embed another webpage inside your webpage**

---

## 2. Basic Syntax

```html id="x1yqz8"
<iframe src="https://example.com"></iframe>
```

---

## 3. Example

```html id="v7k3dp"
<iframe src="https://www.google.com"></iframe>
```

👉 Displays another website inside your page

---

## 4. Important Attributes

```html id="6o3p9n"
<iframe 
    src="https://example.com" 
    width="600" 
    height="400">
</iframe>
```

### 🔹 Attributes:

* `src` → URL of the page
* `width` → Width of iframe
* `height` → Height of iframe

---

## 5. Remove Border

```html id="o8c2mf"
<iframe src="https://example.com" style="border: none;"></iframe>
```

👉 Removes default border

---

## 6. Use Cases

* Embed **YouTube videos**
* Show **maps (Google Maps)**
* Display **other websites/pages**

---

## 7. Navigation Inside iframe (Advanced 🔥)

```html id="r8e1pt"
<iframe name="frame1"></iframe>

<a href="https://example.com" target="frame1">Open</a>
```

👉 Link opens inside iframe

---

## ⚠️ Important Notes

* Some websites **block iframe embedding** (security reasons)
* Use iframe carefully (can affect performance)

---

## 🔥 Final Understanding

> `iframe` is used to embed another webpage inside your webpage

---

## 💡 Pro Tip

Most common real-world use:
👉 Embedding **YouTube video**

```html id="1m9kzq"
<iframe 
    src="https://www.youtube.com/embed/videoID">
</iframe>
```

---
