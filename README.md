# M Grishma - Personal Portfolio

A sleek, responsive, and modern personal portfolio website built with **Astro**, **Tailwind CSS**, and **TypeScript**, showcasing ML infrastructure and AI systems engineering experience.

## 🚀 Tech Stack

- **Framework**: [Astro v5](https://astro.build/) (Static Site Generator)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/) (using `@tailwindcss/vite` compiler integration)
- **Language**: TypeScript
- **Icons**: Inline SVG Icons (for maximum performance and loading speeds)
- **Hosting**: GitHub Pages via GitHub Actions

## 📁 Project Structure

```text
/
├── .github/workflows/
│   └── deploy.yml         # GitHub Actions CI/CD deployment configuration
├── public/
│   ├── favicon.svg        # Site favicon
│   └── grishma_resume.pdf # Downloadable resume PDF
├── src/
│   ├── components/        # Reusable presentation components
│   │   ├── ExperienceItem.astro
│   │   └── ProjectCard.astro
│   ├── layouts/
│   │   └── Layout.astro   # Responsive site shell with theme persistence
│   ├── pages/
│   │   └── index.astro    # Portfolio sections (Hero, About, Experience, Projects, Skills)
│   └── styles/
│       └── global.css     # Global styles and Tailwind custom theme tokens
├── astro.config.mjs       # Astro configuration
├── package.json
└── tsconfig.json
```

## 🧞 Local Development

All commands are run from the root directory:

| Command | Action |
| :--- | :--- |
| `npm install` | Installs project dependencies |
| `npm run dev` | Starts local development server at `http://localhost:4321` |
| `npm run build` | Builds the static website to `./dist/` |
| `npm run preview` | Previews the production build locally |

## 🚀 Deployment

The site is configured to automatically deploy to **GitHub Pages** on every push to the `main` branch. 

To enable this:
1. Ensure the repo is hosted on GitHub (e.g. `github.com/grishmaaa/portfolio`).
2. Go to **Settings** > **Pages** in your GitHub repository.
3. Under **Build and deployment** > **Source**, select **GitHub Actions**.
4. Push any changes to the `main` branch to trigger the deploy workflow.
