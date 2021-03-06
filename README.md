# Strapi Starter Gatsby Blog

Gatsby starter for creating a blog with Strapi.

![screenshot image](/screenshot.png)

This starter allows you to try Strapi with Gatsby with the example of a simple blog. It is fully customizable and due to the fact that it is open source, fully open to contributions. So do not hesitate to add new features and report bugs!

## Features

- 2 Content types: Article, Category
- 2 Created articles
- 3 Created categories
- Responsive design using UIkit
- SEO and social media friendly

Pages:

- "/" to display every articles
- "/article/:id" to display one article
- "/category/:id" display articles depending on the category

## Getting started

The easiest way to try this starter is to run it locally on your computer.

First, you'll need to create your own copy of this starter. You can do so by clicking [the "Use this template" button](https://github.com/strapi/strapi-starter-gatsby-blog/generate) on GitHub, and filling the [form](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template)

### Backend

Follow the instructions [on this repository](https://github.com/strapi/strapi-starter-blog)

### Frontend

Clone your repository:

```bash
git clone <your-github-repo-url>
cd strapi-starter-gatsby-blog
```

Start the frontend server:

```bash
# Using yarn:
yarn install
yarn develop

# Or using npm:
npm install
npm run develop
```

If you want to change the default environment variables, create a `.env` file like this:

```sh
cp .env.example .env
```

The Gatsby server will run here => [http://localhost:3000](http://localhost:3000)

Enjoy this starter!
