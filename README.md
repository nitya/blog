# Nitya Narasimhan's Blog

Experimenting with different platforms and themes to get a personal blog setup for use in sharing ongoing projects and interests. 

## Requirements

 - Minimal and clean appearance
 - Accessible by default, with fast build/deploy times
 - Support RSS feeds, tags, time-to-read and author profiles
 - Integrated social sharing, analytics and open-graph headers
 - Uses Markdown for content (with ease of migration if needed)
 - Deploys to GitHub Pages (now) & other hosting options (later)
 - Stable with good community support (themes, debugging etc.)

## Options

I'm currently exploring three different platforms:

> **1. [Docusaurus](https://docusaurus.io)**

Docusaurus is a React-based static site generation framework from Meta that I've ued in [multiple projects in 2022-2023](https://github.com/30DaysOf). I like it's easy of setup and customizability, and the option to create custom components (as a JS dev). But it is overkill for just a blog, and can be slow to build.


> **2. [Astro](https://docusaurus.io)**

Astro is another [rising star](https://risingstars.js.org/2022/en#section-ssg) for JS-based static site generators. It is designed for speed and works well with other frameworks (for components). I have a learning curve to understand it, but using it for a blog gives me a forcing function to learn by using it in a practical app.

> **3. [Hugo](https://gohugo.io)**

Hugo was my [original go-to](https://nitya.github.io/learn-playwright/) for blogs. It has long held the title of _fastest framework for building websites_. It is built with Golang - but as a user, you just configure it & author Markdown content. It also has the largest stable community with [many themes & templates](https://themes.gohugo.io/) to start building with.

_Regardless of the choice, my goal is to keep content in Markdown so I can migrate more easily to a different platform later if needed_.

## Setup

Check out the [SETUP.md](SETUP.md) page to learn more about how _this_ blog was setup, and which option I went with from the three above.