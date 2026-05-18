# sergiolopezballesteros.github.io

> Personal portfolio of **Sergio López Ballesteros** — Frontend Software Engineer · Freelance · 16 years of experience.

[![Live site](https://img.shields.io/badge/live-sergiolopezballesteros.github.io-FFB000?style=flat-square)](https://sergiolopezballesteros.github.io)
[![Status](https://img.shields.io/badge/status-available_for_projects-22c55e?style=flat-square)](mailto:sergiolopezballesteros@gmail.com)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](#license)

A handcrafted single-page portfolio built with plain HTML and Tailwind CSS, designed around a phosphor-amber terminal aesthetic. No build step, no frameworks, no dependencies installed locally — just one HTML file you can open anywhere.

---

## About me

I'm a frontend software engineer with 16 years designing and shipping high-performance web and mobile applications. I specialize in **Angular** (versions 6–18), **Nuxt** (3 and 4), and **Ionic**, with a strong focus on scalable architecture, SSR, performance optimization, and long-term maintenance of products in production.

I work as a freelancer, accompanying clients from the initial technical conception through delivery and continuous evolution of their platforms. Some of the projects I've led or contributed to recently include OTT streaming platforms, large-scale Angular migrations (LaLIGA+), industrial management systems with mobile companion apps (Famaex), and real-time messaging products.

---

## Tech stack

- **HTML5** — semantic markup, no frameworks
- **Tailwind CSS** — loaded via CDN (`cdn.tailwindcss.com`)
- **Google Fonts** — Space Grotesk + Inter + Material Symbols Outlined
- **Vanilla CSS** — custom properties for the amber phosphor palette, CRT scanline overlays, and terminal cursor animations

No build pipeline. No `package.json`. The entire portfolio lives in a single HTML file that works from any modern browser.

---

## Run it locally

```bash
git clone https://github.com/sergiolopezballesteros/sergiolopezballesteros.github.io.git
cd sergiolopezballesteros.github.io
```

Then either open `index.html` directly in your browser.

---

## Deployment

This repo is configured for **GitHub Pages**. Every push to `main` triggers an automatic redeploy within ~1 minute.

To replicate the setup on your own fork:

1. Rename the repository to `<your-username>.github.io`
2. Go to **Settings → Pages**
3. Under "Build and deployment", choose **Deploy from a branch** → `main` → `/` (root)
4. Save and wait for the green checkmark

That's it — HTTPS is automatic via Let's Encrypt, the CDN is GitHub's, and there's no configuration file required.

---

## Featured projects (shown in the portfolio)

A short index of the work referenced inside the site:

- **OTT Streaming Platform** — technical lead from scratch. Architecture design, SSR with Nuxt 3, state management with Pinia, later migration to Nuxt 4.
- **LaLIGA+** — streaming content platform. Progressive migration from Angular 7 to Angular 17 while keeping the service in production.
- **Famaex** — Angular 7 and 11 web platforms for internal management and field services. Ionic 3/4 mobile apps that digitalized field work. Backend with Ruby on Rails 6/7.
- **My Vitale** — instant messaging web platform with Angular 8 and CometChat integration.
- **El Buen Inquilino** — module and component design and implementation for an internal management platform with Angular 18.

---

## Contact

- **Email** — [sergiolopezballesteros@gmail.com](mailto:sergiolopezballesteros@gmail.com)
- **LinkedIn** — [linkedin.com/in/sergio-lopez-ballesteros](https://linkedin.com/in/sergio-lopez-ballesteros)

Currently available for new freelance projects. Whether it's a long-term engagement, a tricky migration, or a greenfield architecture, feel free to reach out.

---

## License

The **code** in this repository is released under the [MIT License](./LICENSE) — feel free to fork it, study it, and adapt it as a starting point for your own portfolio.

The **content** (personal information, project descriptions, professional history, and identity) is © Sergio López Ballesteros and is not covered by the MIT License. If you fork this, please replace it with your own.
