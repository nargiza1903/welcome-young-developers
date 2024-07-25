
## More CSS ✨

### Discover advanced CSS techniques for layouts and cool effects.

### 1. Flexbox Layout

**Objective:** Learn how to create flexible and responsive layouts using CSS Flexbox.

#### Example: Creating a Responsive Navigation Bar

**Step-by-Step Guide:**

1. **HTML Structure:**
    - Start by creating a basic HTML structure with a `nav` element for the navigation bar.
    - Inside the `nav`, add a `div` for the logo and an `ul` for the navigation links.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexbox Navigation Bar</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <nav class="navbar">
        <div class="logo">MyLogo</div>
        <ul class="nav-links">
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
</body>
</html>
```

2. **CSS Styling:**
    - Use Flexbox to style the navigation bar.
    - Set `display: flex` on the `.navbar` to align its children (logo and navigation links) in a row.
    - Use `justify-content: space-between` to place the logo on the left and the navigation links on the right.
    - Style the links to make them visually appealing.

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #333;
    padding: 10px;
}

.logo {
    color: white;
    font-size: 1.5em;
}

.nav-links {
    list-style: none;
    display: flex;
}

.nav-links li {
    margin-left: 20px;
}

.nav-links a {
    color: white;
    text-decoration: none;
    padding: 5px 10px;
    transition: background 0.3s;
}

.nav-links a:hover {
    background: #575757;
    border-radius: 5px;
}
```

### 2. CSS Grid Layout

**Objective:** Understand the CSS Grid layout to create complex web page layouts.

#### Example: Basic Grid Layout

**Step-by-Step Guide:**

1. **HTML Structure:**
    - Create a basic HTML structure with a `div` container and several child `div` elements for different sections of the layout.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grid Layout Example</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="grid-container">
        <div class="item1">Header</div>
        <div class="item2">Menu</div>
        <div class="item3">Main</div>
        <div class="item4">Right</div>
        <div class="item5">Footer</div>
    </div>
</body>
</html>
```

2. **CSS Styling:**
    - Use CSS Grid to define the layout.
    - Set `display: grid` on the container and use `grid-template-areas` to define the layout areas.
    - Assign each child `div` to a grid area using the `grid-area` property.

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.grid-container {
    display: grid;
    grid-template-areas:
        'header header header'
        'menu main right'
        'footer footer footer';
    grid-gap: 10px;
    padding: 10px;
}

.grid-container > div {
    background-color: #4CAF50;
    color: white;
    padding: 20px;
    text-align: center;
}

.item1 { grid-area: header; }
.item2 { grid-area: menu; }
.item3 { grid-area: main; }
.item4 { grid-area: right; }
.item5 { grid-area: footer; }
```

### 3. CSS Transitions and Animations

**Objective:** Learn to add smooth transitions and animations to web elements.

#### Example: Hover Animation

**Step-by-Step Guide:**

1. **HTML Structure:**
    - Create a simple HTML structure with a `div` element for the box.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hover Animation</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="box"></div>
</body>
</html>
```

2. **CSS Styling:**
    - Style the box and use the `transition` property to define a smooth animation when hovering.
    - Use the `transform` property to scale the box on hover.

```css
body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: #f0f0f0;
}

.box {
    width: 100px;
    height: 100px;
    background-color: #333;
    transition: transform 0.3s;
}

.box:hover {
    transform: scale(1.2);
}
```

### 4. Hands-on Projects

**Objective:** Apply the learned techniques in real-world projects to reinforce understanding.

#### Project: Design a Portfolio Page

**Instructions:**
1. Create a new HTML file for your portfolio page.
2. Use Flexbox and Grid layouts to structure your page.
3. Add animations and transitions to enhance the user experience.
4. Include sections like About Me, Projects, and Contact.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="header">About Me</header>
    <section class="projects">Projects</section>
    <section class="contact">Contact</section>
</body>
</html>
```

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.header {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 200px;
    background-color: #4CAF50;
    color: white;
    font-size: 2em;
}

.projects, .contact {
    padding: 20px;
}

.projects {
    background-color: #f0f0f0;
}

.contact {
    background-color: #e0e0e0;
}
