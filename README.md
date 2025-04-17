# 🌱 NuxtRecipes - Nuxt 3 + Tailwind CSS App

A clean and modern web application built with **Nuxt 3**, styled using **Tailwind CSS**. Perfect for practicing Nuxt features like routing, layouts, components, and data fetching.

## 📖 Table of Contents

- [📝 Description](#-description)
- [✨ Features](#-features)
- [⚙️ Requirements](#️-requirements)
- [📥 Installation](#-installation)
- [🚀 Usage](#-usage)
- [📦 Technologies](#-technologies)
- [🤝 Contributing](#-contributing)

---

## 📝 Description

This project is a small recipe-themed Nuxt 3 app — designed to help you learn and play with:

- Pages & layouts
- Nuxt’s `<script setup>`
- TailwindCSS for styling
- `useFetch` and `useAsyncData` for SSR-friendly API calls
- Nuxt Image Module
- Basic routing and navigation

---

## ✨ Features

- ⚡ Built with Nuxt 3 Composition API (`<script setup>`)
- 🎨 Styled with TailwindCSS
- 🖼️ Optimized images using `@nuxt/image`
- 🔗 Client-side navigation with `<NuxtLink>`
- 🌍 API integration using `$fetch` and `useFetch`
- 💥 Custom 404 and error pages

---

## ⚙️ Requirements

- **Node.js** >= 18.x
- **npm** >= 9.x _(or yarn/pnpm if preferred)_

---

## 📥 Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/rubatista/nuxtcipes.git
   cd nuxtcipes
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open in browser:
   ```
   http://localhost:3000
   ```

---

## 🚀 Usage

This app fetches sample recipe data from [dummyjson.com](https://dummyjson.com/docs/recipes), displaying them in a grid with info like:

- Cooking time ⏱️
- Calories 🔥
- Ratings ⭐

Clicking "Browse Recipes" would ideally lead to a full recipes list (to be extended).

---

## 📦 Technologies

- [Nuxt 3](https://nuxt.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Nuxt Image Module](https://image.nuxt.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [DummyJSON](https://dummyjson.com/) for mock API data

---

## 🤝 Contributing

Have an idea or want to improve the app?

1. Fork this repo
2. Create your feature branch
   ```bash
   git checkout -b new-feature
   ```
3. Commit your changes
   ```bash
   git commit -m "Add cool feature"
   ```
4. Push to the branch
   ```bash
   git push origin new-feature
   ```
5. Open a Pull Request 🎉
   <br><br><br>

---

> 🔗
> **_Learned a lot from [this video](https://www.youtube.com/watch?v=RAJZOqr3JZU) — shoutout to the creator!_**
