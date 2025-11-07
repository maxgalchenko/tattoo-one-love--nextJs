# Tattoo One Love – Next.js Frontend

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-10-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-17-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Emotion](https://img.shields.io/badge/Emotion-11-DB7093?style=for-the-badge)
![SWR](https://img.shields.io/badge/SWR-0.3-000000?style=for-the-badge)
![ESLint](https://img.shields.io/badge/ESLint-Airbnb-4B32C3?style=for-the-badge&logo=eslint)
![Prettier](https://img.shields.io/badge/Prettier-2.2-1A2C34?style=for-the-badge&logo=prettier)
![Node.js](https://img.shields.io/badge/Node.js-18.17.0-339933?style=for-the-badge&logo=node.js)

</div>

## Overview

Marketing website frontend for Tattoo One Love. Built with Next.js (pages router) and Emotion, consuming a Strapi backend for content with SEO via `next-seo`.

## Key Features

- SEO-friendly pages with SSR and `next-seo`
- Responsive theming with Emotion and a custom breakpoint provider
- Strapi-powered content (messages, policies, gallery/works)

## Tech Stack

React 17, Next.js 10, Node.js 18, Emotion 11, SWR 0.3, react-slick

## Architecture

Next.js Pages Router (`pages/`), client-side data via `StrapiService` using `NEXT_PUBLIC_API_URL`, Emotion theme + global styles, image domains configured in `next.config.js`, SEO defaults via `next-seo`.

## Performance & Accessibility

Leverages Next.js code-splitting and image optimization; semantic markup and `eslint-plugin-jsx-a11y` to encourage accessible components.

## Quality

- Linting: ESLint (Airbnb) • Formatting: Prettier

## Prerequisites

- Node.js: `18.17.0`

## Installation

```bash
git clone https://github.com/maxgalchenko/tattoo-one-love--nextJs.git
cd tattoo-one-love--nextJs
npm install
```

## Environment Variables

```env
NEXT_PUBLIC_API_URL=https://admin.tattooonelove.com
```

## Quick Start

```bash
npm run dev
# Production
npm run build
npm start
```
Open http://localhost:3000

## Available Scripts

- `npm run dev` – Start the Next.js development server
- `npm run build` – Build the app for production
- `npm start` – Run the production server
- `npm run lint` – Lint the codebase with ESLint

## Screenshots

![Main](./public/Hero/menu.jpg)
![404](./public/404.jpg)

---

<div align="center">

Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>
