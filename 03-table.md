# 📘 Tables

---

## 1. Basic Table Tags

```html id="1dzp2q"
<table>
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>Karthik</td>
        <td>22</td>
    </tr>
</table>
```

---

## 🧠 Explanation

* `<table>` → Creates table
* `<tr>` → Table row
* `<th>` → Table heading (bold + center)
* `<td>` → Table data (normal cell)

---

## 2. Table Structure Tags

```html id="c9wx62"
<table>
    <caption>Student Data</caption>
    
    <thead>
        <tr>
            <th>Name</th>
            <th>Age</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td>Karthik</td>
            <td>22</td>
        </tr>
    </tbody>
</table>
```

---

## 🧠 Explanation

* `<caption>` → Title of table
* `<thead>` → Heading section
* `<tbody>` → Body content

👉 Helps in **clean structure + better readability + SEO**

---

## 3. colspan (Column Span)

```html id="1i0vhc"
<tr>
    <th colspan="2">Student Info</th>
</tr>
```

👉 Merges **columns**

---

## 4. rowspan (Row Span)

```html id="fs0yyg"
<tr>
    <td rowspan="2">Karthik</td>
    <td>22</td>
</tr>
<tr>
    <td>23</td>
</tr>
```

👉 Merges **rows**

---

## 5. Adding Border

### 👉 Old Method (HTML)

```html id="pv6kqk"
<table border="1">
```

👉 Works but ❌ not recommended

---

### 👉 Best Method (CSS)

```html id="fs25dc"
<table style="border: 1px solid black;">
```

OR

```html id="v9x9ql"
<table>
    <tr>
        <td style="border: 1px solid black;">Data</td>
    </tr>
</table>
```

---

## 💡 Pro Tip (Important 🔥)

To make clean borders:

```html id="0b2qzh"
<table style="border-collapse: collapse;">
```

👉 Removes double borders

---

## 🔥 Final Understanding

* Table = `<table>`
* Row = `<tr>`
* Heading = `<th>`
* Data = `<td>`
* Structure = `<thead>`, `<tbody>`
* Merge = `colspan`, `rowspan`
* Border → Use CSS (not HTML attribute)

---

## ⚡ Simple Memory Trick

👉 **T R H D**

* T → table
* R → row
* H → heading
* D → data


