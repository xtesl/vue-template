# Vue 3 + Vite + TailwindCSS Starter Template

A modern, lightweight Vue 3 starter template pre-configured with Vite, TailwindCSS, and Vue Router. Perfect for quickly bootstrapping new Vue projects with best practices and zero configuration hassle.

## ✨ Features

- ⚡️ **Vue 3** - Progressive JavaScript framework with Composition API
- 🚀 **Vite** - Next generation frontend tooling for lightning-fast HMR
- 🎨 **TailwindCSS** - Utility-first CSS framework for rapid UI development
- 🧭 **Vue Router** - Official routing solution for seamless navigation
- 📦 **Script Setup** - Simplified component syntax with `<script setup>`
- 🔥 **Hot Module Replacement** - Instant feedback during development
- 🏗️ **Optimized Build** - Production-ready builds with code splitting

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v16.0 or higher) - [Download here](https://nodejs.org/)
- **npm** (v7.0 or higher) or **yarn** (v1.22 or higher)

## 🚀 Getting Started

### 1. Clone or Use This Template

```bash
# Clone the repository
git clone https://github.com/xtesl/vue-template.git
cd vue-router
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
```

### 3. Start Development Server

```bash
npm run dev
# or
yarn dev
```

Your application will be running at `http://localhost:5173`

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with hot reload |
| `npm run build` | Build for production in `dist/` folder |
| `npm run preview` | Preview production build locally |

## 🗂️ Project Structure

```
├── public/             # Static assets
├── src/
│   ├── assets/        # Images, fonts, etc.
│   ├── components/    # Reusable Vue components
│   ├── router/        # Vue Router configuration
│   ├── views/         # Page components
│   ├── App.vue        # Root component
│   ├── main.js        # Application entry point
│   └── style.css      # Global styles & Tailwind imports
├── index.html         # HTML entry point
├── package.json       # Dependencies and scripts
├── tailwind.config.js # TailwindCSS configuration
└── vite.config.js     # Vite configuration
```

## 🎨 TailwindCSS Usage

TailwindCSS is pre-configured and ready to use. Simply add utility classes to your components:

```vue
<template>
  <div class="flex items-center justify-center min-h-screen bg-gray-900">
    <h1 class="text-4xl font-bold text-white">Hello World</h1>
  </div>
</template>
```

### Customizing Tailwind

Edit `tailwind.config.js` to customize your theme:

```js
export default {
  theme: {
    extend: {
      colors: {
        primary: '#your-color',
      },
    },
  },
}
```

## 🧭 Routing

Vue Router is pre-configured with a basic setup. Add new routes in `src/router/index.js`:

```js
const routes = [
  {
    path: '/',
    name: 'Home',
    component: () => import('../views/HomeView.vue')
  },
  {
    path: '/about',
    name: 'About',
    component: () => import('../views/AboutView.vue')
  }
]
```

## 🏗️ Building for Production

```bash
npm run build
```

This will generate optimized static files in the `dist/` directory, ready for deployment.

### Preview Production Build

```bash
npm run preview
```

## 🚢 Deployment

The `dist/` folder can be deployed to any static hosting service:

- **Vercel**: `vercel deploy`
- **Netlify**: Drag and drop `dist/` folder
- **GitHub Pages**: Use [gh-pages](https://www.npmjs.com/package/gh-pages)
- **Firebase Hosting**: `firebase deploy`

## 💡 IDE Setup

### Recommended IDE

**[VS Code](https://code.visualstudio.com/)** with the following extensions:

- [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) - Vue 3 language support
- [TailwindCSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) - Tailwind class autocomplete

### Disable Vetur

If you have Vetur installed, disable it to avoid conflicts with Volar.

## 📚 Learn More

- [Vue 3 Documentation](https://vuejs.org/)
- [Vite Documentation](https://vitejs.dev/)
- [TailwindCSS Documentation](https://tailwindcss.com/)
- [Vue Router Documentation](https://router.vuejs.org/)
- [Composition API Guide](https://vuejs.org/guide/extras/composition-api-faq.html)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📝 License

This project is [MIT](LICENSE) licensed.

---

**Happy Coding! 🎉**