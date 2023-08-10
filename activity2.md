# **Activity 2: Designing a Finance Page**

## **Objective**

Introduce beginners to advanced semantic HTML elements and CSS properties through the design of a simple finance-themed webpage.

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

In `finance.css`, build upon the previous styles and add new ones:

```css
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #e6e6e6;
}

header {
    position: relative;
    text-align: center;
    color: white;
}

header img {
    width: 100%;
    height: auto;
}

header h1 {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 2em;
    background-color: rgba(0,0,0,0.7);
    padding: 10px;
    border-radius: 5px;
}

nav ul {
    background-color: #333;
    overflow: auto;
    color: white;
    padding: 0;
    text-align: center;
    margin: 0;
}

nav li {
    display: inline;
}

nav a {
    display: inline-block;
    width: 33.3%;
    padding: 12px 24px;
    color: white;
    text-decoration: none;
}

nav a:hover {
    background-color: #555;
}

main {
    background-color: #FFF;
    padding: 20px;
    margin: 20px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}

```

### 4. **Preview & Discuss**

- Open the `finance.html` in a web browser.
- Observe how semantic tags organize content and how CSS enhances its appearance.
- Discuss:
  - The role of each semantic tag.
  - How the new CSS properties (`position`, `transform`, `background-color with rgba`, etc.) affected the layout and design.

## **Extensions**

1. Add more images for each section in the article.
2. Experiment with different `:hover` effects for navigation links.
3. Try using a gradient background for the `nav` or `footer`.

---

You can place this markdown directly into a section of your `README.md` on GitHub after the previous activity. The learners will then have a continuous learning experience, first with the blog page and then with the finance page.
