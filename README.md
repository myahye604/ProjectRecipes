Odin Recipes 🍽️
A beginner HTML project built as part of The Odin Project Foundations curriculum. The goal is to practice core HTML skills by building a simple multi-page recipe website — no CSS, no JavaScript, just clean, semantic HTML.

🎯 Project Goals

Understand the structure of a well-formed HTML document (boilerplate, <!DOCTYPE>, <head>, <body>)
Practice creating and organizing multiple HTML files within a project directory
Build navigation between pages using relative links (<a href="...">)
Use semantic HTML elements: headings, paragraphs, lists (ordered and unordered), and images
Learn how file paths work — both linking to subpages and linking back to a parent directory


📚 What This Project Teaches
1. HTML Document Structure
Every page in this project follows the standard HTML boilerplate — <!DOCTYPE html>, <html>, <head> with a <title>, and a <body>. Repeating this across multiple files builds the habit of writing well-formed HTML from scratch.
2. Relative File Paths & Linking
The project introduces how to link between pages using relative paths:

From the index to a recipe page: href="recipes/lasagna.html"
From a recipe page back to the index: href="../index.html"

Understanding directory structure and how paths resolve is a foundational web development skill.
3. Semantic HTML Elements
Each recipe page practices a variety of HTML elements in context:

<h1>, <h2> — page and section headings
<img> — embedding images with src and alt attributes
<p> — descriptive paragraphs
<ul> — unordered lists for ingredients
<ol> — ordered lists for step-by-step instructions

4. Site Navigation
The index page links to all two recipes using an unordered list of anchor tags, and each recipe page links back home — introducing the concept of consistent site navigation.

🗂️ Project Structure
odin-recipes/
├── index.html
└── recipes/
    ├── lasagna.html
    ├── spaghetti-bolognese.html
    └── [third-recipe].html

🔄 Project Iterations
The project is built incrementally across four iterations:
IterationWhat You Build1index.html with an <h1> heading2A recipes/ directory with one recipe page; link it from the index and add a back link3Add content to the recipe page: image, description, ingredients list, steps list4Add two more recipe pages; update the index with an unordered list of all three links

🚀 How to View
No build tools or servers needed. Simply open index.html in any web browser:
bash# Clone the repo
git clone https://github.com/your-username/odin-recipes.git

# Open in browser
open odin-recipes/index.html
Or drag and drop index.html into your browser window.

🛠️ Built With

HTML5 — and nothing else. That's the point.


📖 Part of The Odin Project
This project is the first assignment in The Odin Project Foundations course — a free, open-source full-stack curriculum. If you're learning web development, check it out.