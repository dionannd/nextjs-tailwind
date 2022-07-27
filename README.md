<div align="center">
  <h1>ts-nextjs-tailwind-starter</h1>
  <p>Next.js + Tailwind CSS + TypeScript starter packed.</p>
  
  
  [![CodeFactor](https://www.codefactor.io/repository/github/dionannd/ts-nextjs-tailwind-starter/badge/main)](https://www.codefactor.io/repository/github/dionannd/ts-nextjs-tailwind-starter/overview/main)
  [![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=dionannd_ts-nextjs-tailwind-starter&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=dionannd_ts-nextjs-tailwind-starter)
  [![Bugs](https://sonarcloud.io/api/project_badges/measure?project=dionannd_ts-nextjs-tailwind-starter&metric=bugs)](https://sonarcloud.io/dashboard?id=dionannd_ts-nextjs-tailwind-starter)
  [![Depfu](https://badges.depfu.com/badges/fc6e730632ab9dacaf7df478a08684a7/overview.svg)](https://depfu.com/github/dionannd/ts-nextjs-tailwind-starter?project_id=30160)
</div>

## Features

- Next.js 12
- React 18
- TypeScript
- Tailwind CSS 3 — Configured with CSS Variables to extend the **primary** color
- Pre-built Components — Components that will **automatically adapt** with your brand color
- Husky & Lint Staged — Run scripts on your staged files before they are committed
- Conventional Commit Lint — Make sure you & your teammates follow conventional commit
- Automatic Branch and Issue Autolink — Branch will be automatically created on issue **assign**, and auto linked on PR
- Default Open Graph — Awesome open graph generated using [og](https://github.com/dionannd/og), fork it and deploy!
- Site Map — Automatically generate sitemap.xml

## Getting Started

### 1. Clone this template using one of the three ways:

1. Use this repository as template

   ![Use as template](https://user-images.githubusercontent.com/55318172/129183039-1a61e68d-dd90-4548-9489-7b3ccbb35810.png)

2. Using `degit`

   ```bash
   npx degit dionannd/ts-nextjs-tailwind-starter YOUR_PROJECT_NAME
   ```

3. Deploy to Vercel

   [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2Fdionannd%2Fts-nextjs-tailwind-starter)

### 2. Install dependencies

It is encouraged to use **yarn** so the husky hooks can work properly.

```bash
yarn install
```

### 3. Run the development server

You can start the server using this command:

```bash
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result. You can start editing the page by modifying `src/pages/index.tsx`.

### 4. Change defaults

There are some things you need to change including title, urls, favicons, etc.

Find all comments with !STARTERCONF, then follow the guide.

Don't forget to change the package name in package.json

### 5. Commit Message Convention

This starter is using [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/), it is mandatory to use it to commit changes.
