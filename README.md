# React Small Apps

A collection of small React applications built with [Remix](https://remix.run), a full-stack web framework that leverages React for building fast, modern web experiences.

## Overview

This project demonstrates Remix patterns and React best practices through concise, focused examples. It is configured for seamless deployment to [Vercel](https://vercel.com) with zero configuration.

## Tech Stack

- **Framework:** Remix
- **UI Library:** React 18
- **Language:** TypeScript
- **Deployment:** Vercel
- **Analytics:** Vercel Analytics

## Getting Started

### Prerequisites

- Node.js 14 or higher
- npm, yarn, or pnpm

### Installation

```sh
npm install
```

### Development

Start the development server:

```sh
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Production Build

```sh
npm run build
```

## Deployment

### Deploy to Vercel

The easiest way to deploy is with Vercel:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/vercel/tree/main/examples/remix&template=remix)

Alternatively, deploy using the [Vercel CLI](https://vercel.com/cli):

```sh
npm i -g vercel
vercel
```

## Project Structure

```
app/
  entry.client.tsx   # Client-side entry point
  entry.server.tsx   # Server-side entry point
  root.tsx           # Root component
  routes/            # Route components
public/              # Static assets
```

## License

MIT
