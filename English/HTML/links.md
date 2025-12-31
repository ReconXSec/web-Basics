
# 📚 HTML Links

**Date:** December 31, 2025  
**Level:** Beginner  
**Status:** 🟢 Completed  

---

## 🎯 Goals / Objectives

* Understand how to create links using the `<a>` tag.  
* Learn the main attributes such as `href`, `target`, and `title`.  
* Know how to link internal pages, jump to specific sections using `id`, and create special links like email links.  
* Recognize the importance of links in navigating between pages and content on a website.  

---

## 📝 Summary & Core Concepts

Links are the foundation of navigation on the web. With the `<a>` tag, you can:  
- Navigate to external websites (e.g., Google).  
- Link to internal pages within your own site.  
- Jump directly to specific sections of a page using `id`.  
- Create email links using `mailto:`.  

### 📑 Key Concepts
* **`<a>`**: The anchor tag used to create links.  
* **`href`**: Defines the destination of the link (URL, internal page, or email).  
* **`target="_blank"`**: Opens the link in a new tab or window.  
* **`title`**: Tooltip text shown when hovering over the link.  
* **`id`**: A unique identifier for an element, used for direct navigation.  
* **`mailto:`**: Creates a link that opens the default email client to send a message.  

---

## ⚙️ Practical Commands & Examples

### 1. External Link
```html
<a href="https://www.google.com/">Google</a>
```
**Result:** Displays "Google" as clickable text. Clicking opens Google in the same tab.  

---

### 2. Open Link in a New Tab
```html
<a href="https://www.google.com" target="_blank">Google</a>
```
**Result:** Clicking opens Google in a new tab, keeping the current page open.  

---

### 3. Add a Tooltip with `title`
```html
<a href="https://www.google.com" target="_blank" title="Go to Google">Google</a>
```
**Result:** Hovering over the link shows "Go to Google" as a tooltip.  

---

### 4. Link to an Internal Page
```html
<a href="index.html" title="Go to Index">Index</a>
```
**Result:** Navigates to an internal page named `index.html`.  

---

### 5. Link to a Section with `id`
```html
<p id="section40">Hello, I am Bilal...</p>
<a href="#section40" title="Go to text">Jump to Text</a>
```
**Result:** Clicking jumps directly to the paragraph with `id="section40"`.  

---

### 6. Email Link
```html
<a href="mailto:example@example.com" title="Send Email">Email Me</a>
```
**Result:** Opens the default email client to send a message to `example@example.com`.  

---

## 📊 Outcomes & Key Takeaways

* Links are essential for navigation in HTML.  
* Use `target="_blank"` for external links to avoid losing the current page.  
* The `title` attribute improves user experience by providing extra context.  
* `id` allows quick navigation to specific sections of a page.  
* `mailto:` enables direct email communication through links.  

---

## 🔗 Keywords & Resources

### 🏷️ Keywords / Tags
`HTML`, `Links`, `Anchor`, `Href`, `Target`, `Title`, `Email`, `Web_Development`

### 📚 Further Reading
1. [MDN Web Docs - HTML a element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a)  
2. [W3Schools - HTML Links](https://www.w3schools.com/html/html_links.asp)
