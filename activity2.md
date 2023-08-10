
# **Activity 2: Designing a Finance Page**

## **Objective**

Enhance beginners' knowledge of semantic HTML elements and CSS properties by designing a basic finance-themed webpage.

## **Prerequisites**

- Understanding of basic HTML tags and previous CSS properties introduced.
- A basic understanding of how to add images to web pages.

## **Materials**

- A code editor (e.g., Notepad++, Visual Studio Code, Sublime Text).
- A web browser for preview.
- Image assets (These can be sourced from royalty-free sites like [Unsplash](https://unsplash.com/) or [Pexels](https://www.pexels.com/)).

## **Steps**

### 1. **Setup**

- Create a new folder named `FinancePage`.
- Inside this folder, create two files: `finance.html` and `finance.css`.
- Download and place an image inside this folder (e.g., `finance-header.jpg`).

### 2. **HTML Structure**

In `finance.html`, structure the content:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Finance Tips</title>
    <link rel="stylesheet" href="finance.css">
</head>
<body>
    <header>
        <img src="finance-header.jpg" alt="Money and finance-related items">
        <h1>Personal Finance Tips</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">Budgeting</a></li>
            <li><a href="#">Saving</a></li>
            <li><a href="#">Investing</a></li>
        </ul>
    </nav>
    <main>
        <article>
            <h2>The Importance of Budgeting</h2>
            <section>
                <h3>Understanding Your Expenses</h3>
                <p>Here's why understanding your expenses is crucial...</p>
            </section>
            <section>
                <h3>Setting Financial Goals</h3>
                <p>Setting clear financial goals will help you...</p>
            </section>
        </article>
    </main>
    <footer>
        <p>&copy; 2023 Financial Wisdom</p>
    </footer>
</body>
</html>
```

### 3. **CSS Styling**

In `finance.css`, build upon the previous styles and keep it simple:

```css
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #e6e6e6;
}

header {
    background-color: #333;
    padding: 10px;
    text-align: center;
    color: white;
}

header img {
    width: 100%;
    display: block;
    margin: 0 auto;
}

nav ul {
    background-color: #444;
    padding: 0;
    margin: 0;
    text-align: center;
    list-style-type: none;
}

nav li {
    display: inline;
}

nav a {
    display: inline-block;
    padding: 10px 20px;
    color: white;
    text-decoration: none;
}

nav a:hover {
    background-color: #555;
}

main {
    background-color: #FFF;
    padding: 20px;
    margin: 15px;
}

h2, h3 {
    border-bottom: 1px solid #ddd;
    padding-bottom: 10px;
}

footer {
    background-color: #444;
    color: white;
    text-align: center;
    padding: 10px 0;
}

```

### 4. **Preview & Discuss**

- Open the `finance.html` in a web browser.
- Observe how the semantic tags organize the content and the simplicity of the CSS.
- Discuss:
  - The role of each semantic tag.
  - How the CSS properties applied change the appearance of your content.

## **Extensions**

1. Add a background color to the `article` tag.
2. Adjust the `margin` and `padding` properties for different sections.
3. Experiment with different font sizes for headers.

---

This design is simplified for beginners, focusing on fundamental CSS properties and ensuring that the design remains visually appealing.
