# React Small Apps

A collection of small React applications built with [React Router](https://reactrouter.com), a full-stack web framework that leverages React for building fast, modern web experiences.

## Overview

This project demonstrates React Router patterns and React best practices through concise, focused examples. It is configured for seamless deployment to [Vercel](https://vercel.com) with zero configuration.

## Tech Stack

- **Framework:** React Router 7
- **UI Library:** React 18
- **Language:** TypeScript
- **Deployment:** Vercel
- **Analytics:** Vercel Analytics

## Getting Started

### Prerequisites

- Node.js 20 or higher
- pnpm 7.33.7

### Installation

```sh
pnpm install
```

### Development

Start the development server:

```sh
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Production Build

```sh
pnpm build
```

## Deployment

### Deploy to Vercel

The easiest way to deploy is with Vercel:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/vercel/tree/main/examples/react-router&template=react-router)

Alternatively, deploy using the [Vercel CLI](https://vercel.com/cli):

```sh
pnpm dlx vercel
vercel
```

## Project Structure

```
app/
  routes.ts          # Route configuration
  entry.client.tsx   # Client-side entry point
  entry.server.tsx   # Server-side entry point
  root.tsx           # Root component
  routes/            # Route components
public/              # Static assets
```

## License

MIT
