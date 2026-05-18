# Anime-Review-Website
A simple Anime Review Website built with HTML and CSS featuring ratings, reviews, forms, and modern styling.
# Meenish Anime Review Website 🎌

A beginner HTML + CSS project created as part of my web development learning journey.

This project is an Anime Review Website where users can view anime ratings and submit their own reviews.

## Features

- Anime title and image
- About section
- Top anime list
- Anime rating table
- Review form
- Card style sections
- Gradient background
- Hover effects
- Responsive design basics

## Technologies Used

- HTML5
- CSS3

---

# How To Run This Project

Very simple:

### Step 1
Download or clone the project

### Step 2
Open the project folder

### Step 3
Double-click:

```text
anime.html
```

OR

Open with:

- Chrome
- Edge
- Firefox

The webpage will open in your browser.

---

# Folder Structure

```text
AnimeReview/
│
├── anime.html
├── anime.jpg
└── README.md
```

Keep images inside the same folder.

Use:

```html
<img src="anime.jpg">
```

Do NOT use:

```html
<img src="D:\anime.jpg">
```

because local computer paths only work on your own system.

---

# What I Learned

Through this project I practiced:

- HTML page structure
- CSS styling
- Images
- Tables
- Forms
- Lists
- Card design
- Basic hover effects

---

# Understanding The Design (Simple Explanation)

## Body

```css
body{
margin:0;
font-family:Verdana,sans-serif;
background:linear-gradient(to right,#1a1a2e,#16213e,#0f3460);
color:white;
text-align:center;
}
```

### margin:0

Removes extra space around the page.

### font-family

Changes text style.

### background: linear-gradient

Creates smooth color transition.

Instead of one color:

Blue

It becomes:

Blue → Dark Blue → Navy

### color:white

Makes all text white.

### text-align:center

Centers text.

---

## Container

```css
.container{
width:80%;
margin:auto;
padding:20px;
}
```

Container acts like a large box holding page content.

### width:80%

Content only uses 80% screen width.

### margin:auto

Centers the box.

### padding:20px

Adds space inside.

Without padding:

|text touching border|

With padding:

|   text has space   |

---

## Heading Design

```css
h1{
color:#ffcc00;
font-size:50px;
text-shadow:3px 3px 10px black;
}
```

### font-size

Makes text larger.

### color

Changes title color.

### text-shadow

Adds glow effect behind text.

---

## Image Design

```css
img{
width:300px;
border-radius:15px;
box-shadow:0px 0px 15px white;
}
```

### border-radius

Makes corners rounded.

### box-shadow

Adds glow/shadow.

---

## Card Design

```css
.card{
background-color:rgba(255,255,255,0.1);
padding:20px;
border-radius:20px;
}
```

Cards create modern looking sections.

RGBA means:

- R → Red
- G → Green
- B → Blue
- A → Transparency

---

## Hover Effect

```css
.card:hover{
transform:scale(1.05);
transition:0.5s;
}
```

When mouse touches card:

- Card becomes slightly bigger
- Creates animation effect

---

## Table Design

```css
table{
border-collapse:collapse;
}
```

Makes table borders clean.

---

## Form Design

```css
input,textarea{
width:100%;
padding:10px;
border-radius:10px;
}
```

Makes input boxes:

- wider
- rounded
- easier to use

---

# Areas I Need To Improve

- CSS understanding
- Flexbox
- Responsive layouts
- Semantic HTML
- Better design thinking

---

# Future Improvements

- Add navigation bar
- Add more anime cards
- Add dark/light mode
- Add mobile responsiveness
- Improve animations

---

# Author

Meenish
