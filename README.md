# Luis (luismilabs) - Personal Profile Website

This is the source code for my personal profile website, showcasing my professional journey, investments, and community initiatives.

![Profile Preview](/public/images/banner/cumbi-banner.png)

## 🚀 Features

- **Responsive Design**: Works seamlessly on all devices
- **Dark/Light Mode**: Automatic theme switching based on user preference
- **Social Media Links**: Connect with me on various platforms
- **Ventures & Investments**: Showcase of my investment portfolio
- **SEO Optimized**: Meta tags and structured data for better search engine visibility

## 🛠️ Tech Stack

- [Astro](https://astro.build/) - Static Site Generator
- [TailwindCSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Font Awesome](https://fontawesome.com/) - Icon library

## 🧞 Development Commands

All commands are run from the root of the project, from a terminal:

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:4321`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |

## 📂 Project Structure

```text
/
├── public/
│   ├── images/
│   │   ├── banner/       # Banner images
│   │   ├── logos/        # Logos for ventures and investments
│   │   ├── profile/      # Profile images
│   │   └── socials/      # Custom social media icons
│   ├── favicon.svg       # Site favicon
│   └── robots.txt        # Robots instructions for web crawlers
├── src/
│   ├── components/       # UI components
│   ├── layouts/          # Page layouts
│   ├── pages/            # Astro pages
│   └── styles/           # Global styles
└── package.json
```

## 🚀 Deployment

This site is configured for deployment on AWS. The production build can be generated with:

```bash
npm run build
```

This will create a `dist` directory with all static assets ready to be deployed.

## 📝 License

MIT

---

Developed with ❤️ using [Astro](https://astro.build/)
