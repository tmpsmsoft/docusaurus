---
sidebar_position: 1
---

# Tutorial Intro

Let's discover **Docusaurus in less than 5 minutes**.

# How To Install Docausaurus

To install Docusaurus, a modern documentation site generator, here's what you need to do:

## 🧰 Minimum Requirements

**Node.js 18.0 or above**  

```bash
node -v
```

It's helpful to use a version manager like `nvm` to switch between Node versions easily.

## ⚙️ Installation Steps

### 1. Scaffold Your Website

Create a new site:

```bash
npx create-docusaurus@latest my-website classic
```

Replace `my-website` with your desired folder name.  
`classic` is the recommended template—it includes docs, blog, and custom pages.

### 2. Add TypeScript (Optional)

If you prefer TypeScript, use:

```bash
npx create-docusaurus@latest my-website classic --typescript
```

### 3. Explore Meta Defaults (Optional)

If you’re working on a Meta open source project:

```bash
scarf static-docs-bootstrap
```

## 📂 What You'll Get

After setup, your folder will include:

- `/docs/` for documentation content
- `/blog/` for blog posts
- `/src/pages/` for custom React pages
- `docusaurus.config.js` for site configuration

You can start customizing your content and design immediately!

For more advanced options and flags, run:

```bash
npx create-docusaurus@latest --help
```

You can also check out Docusaurus' installation guide for more details.

---

## I have done `cd my-website` — What is next?

Awesome! 🎉 You’re inside your project folder now—next step is to launch the development server so you can preview your site in the browser.

## 🚀 Start the local dev server

Run this command:

```bash
npm run start
```

It will:

- Compile the project
- Open your browser at `http://localhost:3000`
- Live-refresh as you make changes to docs, pages, or styles

Once it's up, you’ll see your site loaded with some starter content. You can now:

- Edit Markdown files in the `docs/` folder to update documentation
- Tweak layouts or React components in `src/pages/`
- Customize styling in `src/css/custom.css`
