
### Methodology for Project 2: Your Favorite Things Page!

#### Objective
To build a dynamic and visually appealing webpage that reflects students' favorite hobbies, games, movies, or anything they love using HTML and CSS.

#### Tools and Setup
1. **Visual Studio Code (VS Code):** Ensure all students have VS Code installed as their code editor.
2. **GitHub Pages:** Set up a GitHub account and repository to host the webpage.

#### Steps and Content

##### Session 1: Introduction and Planning
1. **Introduction to the Project:**
    - Explain the goal of the project.
    - Show examples of similar webpages for inspiration.

2. **Brainstorming and Planning:**
    - Have students list their favorite hobbies, games, movies, etc.
    - Create a rough sketch of the webpage layout.

##### Session 2: Basic HTML Structure
1. **HTML Basics Refresher:**
    - Review basic HTML tags: `<html>`, `<head>`, `<body>`, `<h1>` to `<h6>`, `<p>`, `<ul>`, `<ol>`, `<li>`, and `<img>`.

2. **Building the Structure:**
    - Create a new HTML file in VS Code.
    - Add the basic HTML structure and necessary meta tags.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Favorite Things</title>
</head>
<body>
    <header>
        <h1>My Favorite Things</h1>
    </header>
    <main>
        <!-- Content will go here -->
    </main>
    <footer>
        <p>&copy; 2024 by [Your Name]</p>
    </footer>
</body>
</html>
```

##### Session 3: Adding Content with HTML
1. **Organizing Content:**
    - Use headings to separate different sections (e.g., Hobbies, Movies, Games).

2. **Adding Text and Images:**
    - Insert paragraphs and images for each favorite thing.

```html
<main>
    <section>
        <h2>Hobbies</h2>
        <p>I love reading, painting, and hiking.</p>
        <img src="path/to/your/image1.jpg" alt="Reading book">
        <img src="path/to/your/image2.jpg" alt="Painting">
    </section>
    <section>
        <h2>Movies</h2>
        <p>My favorite movies are...</p>
        <img src="path/to/your/image3.jpg" alt="Movie poster">
    </section>
    <section>
        <h2>Games</h2>
        <p>I enjoy playing...</p>
        <img src="path/to/your/image4.jpg" alt="Game screenshot">
    </section>
</main>
```

##### Session 4: Styling with CSS
1. **CSS Basics Refresher:**
    - Review CSS syntax and selectors.

2. **External CSS File:**
    - Create a separate CSS file and link it to the HTML file.

```html
<head>
    <link rel="stylesheet" href="styles.css">
</head>
```

3. **Adding Basic Styles:**
    - Style the body, header, footer, and main sections.
    - Apply fonts, colors, and margins/paddings.

```css
/* styles.css */

body {
    font-family: Arial, sans-serif;
    background-color: #f0f8ff;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4682b4;
    color: white;
    text-align: center;
    padding: 1em 0;
}

footer {
    background-color: #4682b4;
    color: white;
    text-align: center;
    padding: 0.5em 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

main {
    padding: 20px;
}

h2 {
    color: #2e8b57;
}

img {
    width: 150px;
    height: auto;
    margin: 10px;
}
```

##### Session 5: Advanced CSS Techniques
1. **CSS Layout Techniques:**
    - Use Flexbox or CSS Grid for advanced layout designs.

```css
main {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

section {
    flex: 1 1 300px;
    margin: 10px;
    padding: 10px;
    border: 1px solid #ccc;
    background-color: #fff;
}
```

2. **Interactive Elements:**
    - Add hover effects to images and links.

```css
img:hover {
    transform: scale(1.1);
    transition: transform 0.3s;
}
```

##### Session 6: Final Touches and Deployment
1. **Review and Testing:**
    - Check for any errors and ensure all links and images work.
    - Validate HTML and CSS code.

2. **Publishing on GitHub Pages:**
    - Commit changes to the GitHub repository.
    - Enable GitHub Pages in the repository settings.

3. **Sharing the Website:**
    - Provide the GitHub Pages URL to share with friends and family.

### Documentation Template

#### Project Title: Your Favorite Things Page!

**Objective:** To build a personalized webpage showcasing favorite hobbies, games, movies, or other interests using HTML and CSS.

**Tools Needed:**
- Visual Studio Code (VS Code)
- GitHub account

**Project Outline:**
1. Introduction and Planning
2. Basic HTML Structure
3. Adding Content with HTML
4. Styling with CSS
5. Advanced CSS Techniques
6. Final Touches and Deployment

**Steps:**

1. **Introduction and Planning:**
    - Explain project goals.
    - Brainstorm and plan webpage content and layout.

2. **Basic HTML Structure:**
    - Create an HTML file with basic structure and meta tags.

3. **Adding Content with HTML:**
    - Organize content using headings and paragraphs.
    - Add images with appropriate alt attributes.

4. **Styling with CSS:**
    - Create and link a CSS file.
    - Apply basic styles to body, header, footer, and main sections.

5. **Advanced CSS Techniques:**
    - Use Flexbox or CSS Grid for layout.
    - Add interactive elements with hover effects.

6. **Final Touches and Deployment:**
    - Review and test the webpage.
    - Publish on GitHub Pages.
    - Share the webpage URL.

### HTML and CSS Template

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Favorite Things</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>My Favorite Things</h1>
    </header>
    <main>
        <section>
            <h2>Hobbies</h2>
            <p>I love reading, painting, and hiking.</p>
            <img src="path/to/your/image1.jpg" alt="Reading book">
            <img src="path/to/your/image2.jpg" alt="Painting">
        </section>
        <section>
            <h2>Movies</h2>
            <p>My favorite movies are...</p>
            <img src="path/to/your/image3.jpg" alt="Movie poster">
        </section>
        <section>
            <h2>Games</h2>
            <p>I enjoy playing...</p>
            <img src="path/to/your/image4.jpg" alt="Game screenshot">
        </section>
    </main>
    <footer>
        <p>&copy; 2024 by [Your Name]</p>
    </footer>
</body>
</html>
```

```css
/* styles.css */

body {
    font-family: Arial, sans-serif;
    background-color: #f0f8ff;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4682b4;
    color: white;
    text-align: center;
    padding: 1em 0;
}

footer {
    background-color: #4682b4;
    color: white;
    text-align: center;
    padding: 0.5em 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

main {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 20px;
}

section {
    flex: 1 1 300px;
    margin: 10px;
    padding: 10px;
    border: 1px solid #ccc;
    background-color: #fff;
}

h2 {
    color: #2e8b57;
}

img {
    width: 150px;
    height: auto;
    margin: 10px;
    transition: transform 0.3s;
}

img:hover {
    transform: scale(1.1);
}
```
