# ADIBID Website

Company website for ADIBID, built with Astro, TypeScript and Tailwind CSS.

## Run locally

```bash
npm install
npm run dev
```

Open http://localhost:4321

## Commands

| Command           | What it does                    |
| ----------------- | ------------------------------- |
| `npm run dev`     | Start the local site            |
| `npm run build`   | Build the site into `dist/`     |
| `npm run preview` | Preview the built site          |

## Folder structure

```text
src/
├── components/
│   ├── common/     Header, Footer
│   ├── sections/   Home page sections
│   └── ui/         Buttons, headings
├── data/           Company info and menu links
├── layouts/        Page layout and SEO
├── pages/          Website pages
└── styles/         Colors and fonts
public/images/      Images and logo
```

## How we work

1. Pull the latest code: `git switch main` then `git pull`
2. Create a branch: `git switch -c feature/your-task`
3. Commit and push your branch
4. Open a pull request on GitHub for review

Do not push directly to `main`.
