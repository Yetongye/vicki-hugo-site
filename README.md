# Vicki Ye's Portfolio Website

This repository contains the **source code** for my personal technical portfolio website, built with [Hugo](https://gohugo.io/) and deployed automatically using **GitHub Actions** to [GitHub Pages](https://yetongye.github.io/).

---

##  Overview

The website includes:

-  **My resume**
-  **Projects** :
  - Product management
  - AI and machine learning applications
  - Full-stack database systems
  - RPA automation systems
-  (Coming soon) **Blog posts** featuring personal reflections and tech notes

---

##  Tech Stack

| Layer         | Technology         |
|---------------|--------------------|
| Static Site   | Hugo               |
| Content       | Markdown + Go Templating |
| Styling/Themes| Hugo Theme Stack   |
| Deployment    | GitHub Actions     |
| Hosting       | GitHub Pages       |

---

##  Deployment Pipeline

Every time I push updates to this repository:

1. GitHub Actions runs Hugo to generate static content.
2. The `public/` folder is created automatically.
3. Static files are pushed to my Pages repo [`Yetongye.github.io`](https://github.com/Yetongye/Yetongye.github.io).
4. Website is updated live at:  
    https://yetongye.github.io/

---

##  How to Contribute or Fork

1. Clone this repo:
   ```bash
   git clone https://github.com/Yetongye/vicki-hugo-site.git
