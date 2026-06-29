# Odin Recipes

A basic recipe website built as part of [The Odin Project](https://www.theodinproject.com/lessons/foundations-recipes) Foundations course. The site has a main index page that links out to several individual recipe pages.

This project is intentionally unstyled — its purpose is to practice writing semantic HTML. CSS styling comes in a later lesson.

## What it does

- An **index page** (`index.html`) that lists and links to each recipe
- Individual **recipe pages** under `recipes/`, each containing:
  - The recipe name as a heading
  - An image of the finished dish
  - A short description
  - An unordered list of ingredients
  - An ordered list of steps
  - A link back to the home page for easy navigation

## Project structure

```
odin-recipes/
├── index.html
├── README.md
└── recipes/
    ├── butter_chicken.html
    ├── carbonara.html
    └── tiramisu.html
```

## Skills demonstrated

- Boilerplate HTML document structure (`<!DOCTYPE html>`, `head`, `body`)
- Headings (`h1`–`h6`) and paragraphs
- Anchor tags and relative linking between pages (including parent-directory paths like `../index.html`)
- Embedding images with `<img>`
- Ordered (`<ol>`) and unordered (`<ul>`) lists
- Organizing a multi-page project into folders
- Using Git and GitHub to version and publish a project

## Running locally

Clone the repository and open `index.html` in any browser:

```bash
git clone git@github.com:your-username/odin-recipes.git
cd odin-recipes
```

Then open `index.html` directly in your browser — no build step or server required.

## Acknowledgements

Recipes and images sourced for practice purposes (e.g. from [Allrecipes](https://www.allrecipes.com/)). Project assignment from The Odin Project.