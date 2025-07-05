# Semantic HTML Project

This project is part of the **ALX Intermediate Frontend** curriculum and focuses on building a strong foundation in **Semantic HTML**, with an emphasis on **accessibility**, **SEO optimization**, and the use of **ARIA roles** for better usability.

---

## 📚 Learning Objectives

- **Master Semantic HTML**: Understand how to structure web content using semantic tags like `<header>`, `<main>`, `<article>`, `<section>`, and `<footer>`.
- **Optimize for SEO**: Improve page visibility using proper meta tags and document structure.
- **Enhance Accessibility**: Use ARIA roles and attributes to make content more accessible to users with disabilities.
- **Understand Form Best Practices**: Create forms that are both accessible and user-friendly.
- **Adopt Incremental Development**: Build the project step-by-step, adding functionality and structure progressively.

---

## ✅ Tasks

### 0. Creating a Structured HTML Document Using Semantic Elements

**File:** `0-index.html`

- Used semantic HTML structure with `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>`.
- Inside `<body>`:
  - A `<header>` contains a `<nav>` with 3 links.
  - A `<main>` contains an `<article>`, which has an `<h1>` and a `<section>`.
  - A `<footer>` with the text `© copyright`.

---

### 1. Enhancing HTML Document with Meta Tags and Title for SEO and Accessibility

**File:** `1-index.html`

- Copied content from `0-index.html`.
- Inside `<head>`:
  - Added `<meta charset="utf-8">`.
  - Added 4 meta tags:
    - `name="description"`: Describes the blog post.
    - `name="keywords"`: HTML, Semantic, Accessibility, Blog, SEO.
    - `name="author"`: Empty for now.
    - `name="viewport"`: For responsive design.
  - Added `<title>`: "Semantic Html Blog Post".

---

### 2. Creating a Blog Post Layout Using Semantic HTML Elements

**File:** `2-index.html`

- Copied content from `1-index.html`.
- In `<header>`:
  - Added `<h1>` with "My Blog".
  - `<nav>` includes `<ul>` with 3 list items for Home, About, Contact.
- In `<main><article>`:
  - Blog post starts with a `<header>` containing:
    - `<h2>`: Understanding Semantic Html
    - `<time>`: Published on September 10
  - First `<section>`:
    - `<h3>`: Introduction
    - `<p>`: Semantic HTML helps improve accessibility and SEO.
  - Second `<section>`:
    - `<h3>`: Main Content
    - `<p>`: Code explanation of semantic elements
    - `<figure>` with `<img>` (empty `src`, alt="example") and `<figcaption>`.
  - Third `<section>`:
    - `<h3>`: Conclusion
    - `<p>`: Recap of benefits of semantic HTML
  - Inside `<article>`, added a `<footer>`:
    - `<p>`: Written by <name>
    - `<p>`: Published on 2024-09-11

---

### 3. Enhancing Form Accessibility with ARIA Roles and Attributes

**File:** `3-index.html`

- Copied content from `2-index.html`.
- Added a new `<section>` inside `<main>` containing a `<form>` with:
  - `action="#"`, `method="POST"`, `role="form"`, `aria-labelledby="form-title"`
  - A heading `<h2 id="form-title">Contact Form</h2>`
  - First `<div>`:
    - `<label for="name">Name:</label>`
    - `<input type="text" id="name" name="name" aria-required="true">`
  - Second `<div>`:
    - `<label for="email">Email:</label>`
    - `<input type="text" id="email" name="email" aria-required="true">`
  - Third `<div>`:
    - `<button type="submit" aria-label="Submit the form">Submit</button>`
  - Fourth `<div>`:
    - `aria-live="polite"` and `role="alert"` for dynamic feedback

---

## 🗂️ Directory Structure

0x00-semantic_html/
├── 0-index.html
├── 1-index.html
├── 2-index.html
├── 3-index.html
└── README.md


---

## 🧠 What You Learned

- How semantic tags improve both structure and accessibility.
- The importance of using correct meta tags for SEO.
- The role of ARIA attributes in creating inclusive web applications.
- Best practices for creating semantic blog posts and accessible forms.
