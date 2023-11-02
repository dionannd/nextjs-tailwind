# Next.js + Tailwind CSS

Next.js + Tailwind CSS + TypeScript Starter Package

[![CodeFactor](https://www.codefactor.io/repository/github/dionannd/nextjs-tailwind/badge)](https://www.codefactor.io/repository/github/dionannd/nextjs-tailwind)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=dionannd_ts-nextjs-tailwind-starter&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=dionannd_ts-nextjs-tailwind-starter)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=dionannd_ts-nextjs-tailwind-starter&metric=bugs)](https://sonarcloud.io/dashboard?id=dionannd_ts-nextjs-tailwind-starter)
[![Depfu](https://badges.depfu.com/badges/b29dfdf091426d02dcee172279403d2e/overview.svg)](https://depfu.com/github/dionannd/ts-nextjs-tailwind-starter?project_id=36174)

## Features

- Next.js 13
- React 18
- TypeScript
- Tailwind CSS 3 — Configured with CSS Variables to extend the **primary** color.
- Pre-built Components — Components that will **automatically adapt** with your brand color.
- Husky & Lint Staged — Run scripts on your staged files before they are committed.
- Conventional Commit Lint — Make sure you & your teammates follow conventional commit.
- Automatic Branch and Issue Autolink — Branch will be automatically created on issue **assign**, and auto linked on PR.
- Default Open Graph — Awesome open graph generated using [og](https://github.com/dionannd/og), fork it and deploy!.
- Site Map — Automatically generate sitemap.xml.

## Getting Started

### 1. Create Next.js app for your project

```shell
npx create-next-app YOUR_PROJECT_NAME -e "https://github.com/dionannd/nextjs-tailwind"
```

### 2. Run the development server

You can start the server using this command:

```bash
yarn dev

# or

npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result. You can start editing the page by modifying `src/pages/index.tsx`.

### 3. Change defaults

There are some things you need to change including title, urls, favicons, etc.

Find all comments with !STARTERCONF, then follow the guide.

Don't forget to change the package name in package.json.

### 4. Commit Message Convention

This starter is using [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/), it is mandatory to use it to commit changes
