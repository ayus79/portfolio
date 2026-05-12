# ayush.portfolio

> yes, i built my own portfolio instead of touching grass. no regrets.

## what is this?

this is my corner of the internet where i pretend to be a professional.  
it's got my projects, my skills, and a typewriter animation because apparently that makes me look cool.

built with **Astro** + **Tailwind CSS** because i refused to use a WordPress template like a normal person.

## stack

- **Astro** — because React was too much javascript for a static page
- **Tailwind CSS** — because writing actual CSS is a form of self-harm
- **JetBrains Mono** — so it looks like i know what i'm doing
- **GitHub Pages** — free hosting, can't complain (i won't pay for this)

## running locally

```bash
# install stuff
npm install

# start the dev server and question your life choices
npm run dev

# build for production (and pray nothing breaks)
npm run build

# preview the build
npm run preview
```

## project structure

```
src/
├── components/
│   ├── Hero.astro       # the "hire me please" section
│   ├── Projects.astro   # things i actually built
│   └── Skills.astro     # things i googled at least twice
├── layouts/
│   └── Layout.astro     # the wrapper that holds it all together
├── pages/
│   └── index.astro      # there's only one page.
└── styles/
    └── global.css       # 90% tailwind, 10% vibes
```

## deploying

pushes to `main` auto-deploy to GitHub Pages via the workflow in `.github/workflows/deploy.yml`.  
it just works. don't touch it.

## license

this code is **not open source**. look, don't touch.  
no forks. no PRs. no "i made it better" submissions.  
this is my portfolio, not a collab project.  

---

*made with caffeine and an unreasonable amount of terminal aesthetics.*
