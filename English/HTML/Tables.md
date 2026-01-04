
# 📚 HTML Tables

**Date:** January 4, 2026  
**Level:** Beginner  
**Status:** 🟢 Completed  

---

## 🎯 Goals / Objectives

* Understand how to create tables using the `<table>` tag.  
* Learn the core elements of tables: `thead`, `tbody`, `tfoot`.  
* Explore additional tags such as `th`, `caption`, and `colspan`.  
* Recognize how to organize data clearly within a table.  

---

## 📝 Summary & Core Concepts

Tables in HTML are used to display data in rows and columns.  
Although styling tables is better handled with CSS, HTML provides the basic structure:  

- **`<table>`**: Starts the table.  
- **`<thead>`**: Header section (column titles).  
- **`<tbody>`**: Main body (actual data).  
- **`<tfoot>`**: Footer section (summary or totals).  
- **`<tr>`**: Table row.  
- **`<td>`**: Table cell (data).  
- **`<th>`**: Table header cell (bold and centered by default).  
- **`<caption>`**: Table title.  
- **`colspan`**: Merges multiple cells into one.  

---

## ⚙️ Practical Commands & Examples

### 1. Simple Table
```html
<table>
  <thead>
    <tr>
      <th>Age</th>
      <th>Job</th>
      <th>Name</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>40</td>
      <td>Engineer</td>
      <td>Oussama</td>
    </tr>
  </tbody>
</table>
```
**Result:** A table with one row and column headers.  

---

### 2. Using `tfoot` for a Summary
```html
<table>
  <thead>
    <tr>
      <th>Product</th>
      <th>Price</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Book</td>
      <td>10$</td>
    </tr>
    <tr>
      <td>Pen</td>
      <td>2$</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>Total</td>
      <td>12$</td>
    </tr>
  </tfoot>
</table>
```
**Result:** A summary row appears at the bottom.  

---

### 3. Adding a Table Title with `caption`
```html
<table>
  <caption>Student List</caption>
  <thead>
    <tr>
      <th>Name</th>
      <th>Grade</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Bilal</td>
      <td>A+</td>
    </tr>
  </tbody>
</table>
```
**Result:** Displays "Student List" above the table.  

---

### 4. Merging Cells with `colspan`
```html
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th colspan="2">Details</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Oussama</td>
      <td>Age: 40</td>
      <td>Job: Engineer</td>
    </tr>
  </tbody>
</table>
```
**Result:** The "Details" header spans two columns.  

---

### 5. Complete Example
```html
<table>
  <caption>Employee Data</caption>
  <thead>
    <tr>
      <th>Name</th>
      <th>Department</th>
      <th>Salary</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Bilal</td>
      <td>IT</td>
      <td>2000$</td>
    </tr>
    <tr>
      <td>Oussama</td>
      <td>HR</td>
      <td>1800$</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="2">Average Salary</td>
      <td>1900$</td>
    </tr>
  </tfoot>
</table>
```
**Result:** A complete table with title, data, and summary.  

---

## 📊 Outcomes & Key Takeaways

* Tables organize data into rows and columns.  
* `thead`, `tbody`, and `tfoot` divide the table into clear sections.  
* `th` highlights headers with bold text.  
* `caption` adds a descriptive title.  
* `colspan` merges cells to expand across multiple columns.  
* CSS is recommended later for professional table styling.  

---

## 🔗 Keywords & Resources

### 🏷️ Keywords / Tags
`HTML`, `Table`, `thead`, `tbody`, `tfoot`, `th`, `caption`, `colspan`, `Web_Development`

### 📚 Further Reading
1. [MDN Web Docs - HTML table element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table)  
2. [W3Schools - HTML Tables](https://www.w3schools.com/html/html_tables.asp)  
