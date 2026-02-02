# magul.ski

Personal website for Tomasz Magulski, built with [Astro](https://astro.build).

## About

A minimalist personal landing page featuring:
- Contact information and social links (LinkedIn, GitHub)
- Clean, centered design
- Static site generation for optimal performance

## Tech Stack

- **Astro** - Static site generator
- **pnpm** - Package manager

## Project Structure

```
.
├── src/
│   └── pages/
│       └── index.astro    # Main landing page
├── public/
│   ├── magullab.css       # Stylesheet
│   └── images/            # Static assets (logos, icons)
├── dist/                  # Production build output
└── package.json
```

## Development

All commands are run from the project root:

```sh
# Install dependencies
pnpm install

# Start development server at localhost:4321
pnpm run dev

# Build for production
pnpm run build

# Preview production build locally
pnpm run preview
```

## Deployment

The site is built as static HTML and can be deployed to any static hosting service. Production files are generated in the `dist/` directory after running `pnpm run build`.
