# CSS Activity 1

Certainly! Here's the exercise formatted in GitHub-flavored Markdown for your `README.md`:

---

# **Styling a Simple Semantic Blog Page**

## **Objective**

Familiarize beginners with the basic principles of styling semantic HTML elements using CSS.

## **Prerequisites**

- Basic understanding of HTML tags.

## **Materials**

- A code editor (e.g., Notepad++, Visual Studio Code, Sublime Text).
- A web browser for preview (e.g., Chrome, Firefox, Safari).

## **Steps**

### 1. **Setup**

- Create a new folder named `SimpleBlog`.
- Inside this folder, create two files: `index.html` and `styles.css`.

### 2. **HTML Structure**

In `index.html`, set up a basic semantic structure for a blog post:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Blog</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>My Blog Title</h1>
    </header>
    <article>
        <h2>Blog Post Title</h2>
        <p>This is the content of my first blog post. I'm learning HTML and CSS!</p>
    </article>
    <footer>
        <p>&copy; 2023 My Simple Blog</p>
    </footer>
</body>
</html>
```

### 3. **Basic Styling with CSS**

In `styles.css`, start with foundational styles:

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header, footer, article {
    background-color: #FFF;
    padding: 20px;
    margin: 20px;
}

h1, h2 {
    color: #333;
}

h1 {
    border-bottom: 2px solid #333;
    padding-bottom: 10px;
}
```

### 4. **Preview & Discuss**

- Open the `index.html` in a web browser.
- Notice how the CSS styles changed the appearance of your blog.
- Discuss:
  - Why did we use tags like `<header>`, `<article>`, and `<footer>`?
  - How did the CSS styles enhance the appearance of the HTML content?

## **Extensions**

1. Change the background color of the body and the text color.
2. Adjust the padding and margins of the `header`, `footer`, and `article` sections.
3. Experiment with different font families for the body and headers.

---


