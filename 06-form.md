# 📘 HTML Notes – Forms

---

## 1. `<form>` Tag

```html
<form action="index.html">
</form>
```

---

## 🧠 Explanation

* Used to **collect user input**
* `action` → where data will be sent after submit

---

## 2. `<label>` Tag

```html
<label for="name">Name:</label>
<input type="text" id="name">
```

👉 Helps in accessibility + clicking label focuses input

---

## 3. `<input>` Tag

```html
<input type="text">
```

👉 Used to take user input

---

## 4. Input Types

```html
<input type="text">
<input type="password">
<input type="date">
<input type="radio">
<input type="checkbox">
```

---

### 🔹 Radio Button

```html
<input type="radio" name="gender"> Male
<input type="radio" name="gender"> Female
```

👉 Same `name` → only one can be selected

---

### 🔹 Checkbox

```html
<input type="checkbox"> Reading
<input type="checkbox"> Gaming
```

👉 Multiple selections allowed

---

## 5. Important Attributes

---

### 🔹 `required`

```html
<input type="text" required>
```

👉 Must be filled before submit

---

### 🔹 `value`

```html
<input type="text" value="Karthik">
```

👉 Default value inside input

---

### 🔹 `disabled`

```html
<input type="text" disabled>
```

👉 Cannot be edited

---

### 🔹 `placeholder`

```html
<input type="text" placeholder="Enter your name">
```

👉 Hint text inside input

---

## 6. Fieldset & Legend

```html
<fieldset>
    <legend>Personal Info</legend>

    <label>Name:</label>
    <input type="text">

</fieldset>
```

---

## 🧠 Explanation

* `<fieldset>` → Groups related inputs
* `<legend>` → Title for the group

👉 Makes form more **structured + user-friendly**

---

# 🔥 Final Understanding

* `<form>` → collects data
* `<input>` → user input
* `<label>` → describes input
* `type` → defines input kind
* `name` → groups radio buttons
* `required`, `placeholder`, etc. → improve UX

---
