
# 📚 Images and Path Handling in HTML (Images & Paths)

**Date:** January 3, 2026  
**Level:** Beginner  
**Status:** 🟢 Completed  

---

## 🎯 Goals / Objectives

* Understand how to insert images into HTML pages using the `<img>` tag.  
* Learn the main attributes such as `src`, `alt`, `width`, and `height`.  
* Know how to handle relative and absolute paths for images.  
* Recognize the importance of the `alt` attribute for accessibility and user experience.  

---

## 📝 Summary & Core Concepts

- **`<img>`**: The tag used to embed images in HTML.  
- **`src`**: Defines the source of the image (file name or path).  
- **`alt`**: Provides alternative text if the image fails to load or for screen readers.  
- **`width` and `height`**: Control the dimensions of the image in pixels.  
- **Paths**: Can be relative (within the project) or absolute (external link).  

---

## ⚙️ Practical Commands & Examples

### 1. Image in the Same Folder
```html
<img src="logo.jpg" alt="Website Logo" width="200" height="150">
```
**Result:** Displays `logo.jpg` from the current folder.  

---

### 2. Image in a Subfolder
```html
<img src="images/photo.png" alt="Profile Photo" width="300" height="200">
```
**Result:** Displays an image from the `images` subfolder.  

---

### 3. Image from a Parent Folder
```html
<img src="../bilal.png" alt="Bilal Photo" width="250" height="250">
```
**Result:** Goes up one folder and displays `bilal.png`.  

---

### 4. Image from an External Link (Absolute Path)
```html
<img src="https://example.com/images/banner.jpg" alt="Website Banner" width="600" height="300">
```
**Result:** Displays an image hosted on another website.  

---

### 5. Image Without Dimensions (Original Size)
```html
<img src="nature.jpg" alt="Nature Landscape">
```
**Result:** Displays the image in its original size.  

---

### 6. Image with Clear Alternative Text
```html
<img src="notfound.png" alt="Image could not be loaded">
```
**Result:** Shows the text if the image is missing.  

---

### 7. Image as a Link Button
```html
<a href="index.html">
    <img src="home.png" alt="Go to Home" width="50" height="50">
</a>
```
**Result:** Clicking the image navigates to the homepage.  

---

## 📊 Outcomes & Key Takeaways

* The `src` attribute defines the image location, either internal or external.  
* The `alt` attribute is essential for accessibility and fallback text.  
* Relative paths are used for project images, while absolute paths are used for external resources.  
* `width` and `height` help control image size, but CSS is recommended for advanced styling.  
* Images can be interactive, serving as links or buttons.  

---

## 🔗 Keywords & Resources

### 🏷️ Keywords / Tags
`HTML`, `Images`, `img`, `src`, `alt`, `width`, `height`, `Relative Path`, `Absolute Path`

### 📚 Further Reading
1. [MDN Web Docs - HTML img element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)  
2. [W3Schools - HTML Images](https://www.w3schools.com/html/html_images.asp)  
