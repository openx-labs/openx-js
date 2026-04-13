# OpenX-Js: The Open Foundation for JavaScript Development

`openx-js` is a collection of high-quality, lightweight, and free open-source
libraries designed to be the foundation for building any application using
JavaScript. Whether you are building for the browser, Node.js, Deno, or Edge
environments, `openx-js` provides the essential building blocks you need to move
fast without reinventing the wheel.

## My Mission

My goal is simple: <b>Provide a suite of foundational tools that are free for
anyone to use, modify, and build upon.</b>

I believe that the best software is built on a solid, open foundation.
`openx-js` aims to provide that foundation by offering a curated set of
libraries that are:

- **Free & Open**: Permissive licensing for everyone, from hobbyists to
  enterprises.
- **Universal**: Built to run anywhere JavaScript runs (Node.js, Browsers, Deno,
  etc.).
- **Lightweight**: Zero or minimal dependencies to keep your bundle size small
  and your supply chain secure.
- **Treeshakeable**: Bundle only the things that you use and discard the rest.
- **Extensible**: Designed as "primitives" that you can easily compose into
  larger systems.

## Library Ecosystem (Coming Soon)

I am currently building out the core categories of libraries. Stay tuned for the
first releases!

### 🛠️ Core Utilities

Essential helpers for common tasks:

- **`@openx/colors`**: A bunch of color classes that allows you to do type-safe
  color interactions.

### 🎨 UI Primitives

Headless, accessible components, utilities for building your own design systems:

- **`@openx/m3-expressive`**: A set of primitives like `ColorScheme`,
  `Typography`, `Shape`, `Elevation`, and others that is recommended by the
  official Google Material 3 design system. Usable in either Vanilla JS or in
  any of your favourite frontend frameworks.

---

## Getting Started

As I release each library, you will be able to install them via your favorite
package manager:

```bash
# In Deno
deno add jsr:@openx/<library-name>

# In Node.js project using NPM
npx jsr add @openx/<library-name>
```

## Contributing

I welcome contributions from the community! `openx` is built by developers, for
developers. If you have an idea for a new library or want to improve an existing
one, please file an issue with all the details and I can guide you on the next
steps.

## License

This project is licensed under the [Apache License 2.0](./LICENSE) - use,
modify, distribute, and sell software for any purpose, including commercial use,
without paying royalties.
