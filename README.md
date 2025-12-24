# Estrocom

A fully responsive, SEO-friendly, WCAG-compliant, and high-performance e-commerce template for businesses. The demo showcases a store for foxnut and roasted gram flour, but it can be adapted for any product. Built with Astro, Tailwind CSS, and TypeScript.

[View live site here]()

---

## 💡 About Me

Hi! I’m Viraj Bijpuria, a developer specializing in modern, fast, and accessible e-commerce solutions. I help businesses launch online stores that look great, perform well, and attract customers.  

If you want a custom store built, or help setting up this template, I can handle everything from design to deployment, from SEO to a11y, from payment integrations to delivery integrations.

[Contact me](mailto:proshowspeed@gmail.com) to get started.

---

## Project Structure

```
├── public/
│ ├── assets/ # All images used
│ └── favicon.svg
├── src/
│ ├── components/
│ │ ├── atoms
│ │ ├── molecules
│ │ └── organisms
│ ├── design-system/
│ ├── layouts/
│ ├── pages/
│ └── utils/
└── package.json
```


[Learn more about Atomic Design](https://bradfrost.com/blog/post/atomic-web-design/)

---

## Getting Started

1. **Add your products**  
   Edit `src/utils/productData.js` with your product details.  

2. **Replace images**  
   Swap the placeholders in `public/assets/` with your own images.  

3. **Update categories & product pages**  
   Edit the frontmatter in `src/pages/category/` and `src/pages/products/`.  

4. **Customize homepage**  
   Edit `src/pages/index.astro` to showcase your story.  

Want me to build it for you? [Reach out](mailto:proshowspeed@gmail.com) and I’ll set up your store quickly.

---

## Commands

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Install dependencies                             |
| `npm run dev`             | Start local server at `localhost:4321`          |
| `npm run build`           | Build production site in `./dist/`              |
| `npm run preview`         | Preview your production build locally           |
| `npm run astro ...`       | Run Astro CLI commands like `astro add` or `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
