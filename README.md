# Alchemy 2024

## Nextjs Learning

### 1. Installation

1. Creating a new project

npx create-next-app@latest nextjs-dashboard --use-npm --example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example"

npx create-next-app@latest nextjs-dashboard --example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example" --use-pnpm
or

npx create-next-app@latest alchemy-nextjs --use-npm

---

### Folder structure

You'll notice that the project has the following folder structure:

- **/app:** Contains all the routes, components, and logic for your application, this is where you'll be mostly working from.
- **/app/lib:** Contains functions used in your application, such as reusable utility functions and data fetching functions.
- **/app/ui:** Contains all the UI components for your application, such as cards, tables, and forms. To save time, we've pre-styled these components for you.
- **/public:** Contains all the static assets for your application, such as images.
- **/scripts:** Contains a seeding script that you'll use to populate your database in a later chapter.
- **Config Files:** You'll also notice config files such as next.config.js at the root of your application. Most of these files are created and pre-configured when you start a new project using create-next-app. You will not need to modify them in this course.

### 2. Styling

- Global CSS: Simple to use and familiar for those experienced with traditional CSS, but can lead to larger CSS bundles and difficulty managing styles as the application grows.
- CSS Modules: Create locally scoped CSS classes to avoid naming conflicts and improve maintainability.
- Tailwind CSS: A utility-first CSS framework that allows for rapid custom designs by composing utility classes.
- Sass: A popular CSS preprocessor that extends CSS with features like variables, nested rules, and mixins.
- CSS-in-JS: Embed CSS directly in your JavaScript components, enabling dynamic and scoped styling.
