# Aggressive Text Waves

> **Note:** This repository exists only for GitHub Pages deployment.
>
> Development happens in the [GenArt Monorepo](https://github.com/MichaelPaulukonis/genart-monorepo). Source code here is not maintained.

---

![Screenshot](screenshot.png)

## Links

- **Live Demo:** [https://michaelpaulukonis.github.io/aggressive-text-waves/](https://michaelpaulukonis.github.io/aggressive-text-waves/)
- **Monorepo:** [https://github.com/MichaelPaulukonis/genart-monorepo](https://github.com/MichaelPaulukonis/genart-monorepo)
- **Source Code:** [apps/aggressive-text-waves/](https://github.com/MichaelPaulukonis/genart-monorepo/tree/main/apps/aggressive-text-waves)
- **Documentation:** [View in monorepo](https://github.com/MichaelPaulukonis/genart-monorepo/tree/main/apps/aggressive-text-waves/README.md)

## About

Text animated on a character grid, driven by 2D Perlin noise. Words from a source text drift across the grid toward wandering gravity sources. Background cells fill with noise-selected punctuation characters.

Built with p5.js as part of the GenArt creative coding collection.

## Development

All development happens in the monorepo:

```bash
git clone https://github.com/MichaelPaulukonis/genart-monorepo.git
cd genart-monorepo
pnpm install
nx dev aggressive-text-waves
```

## License

MIT
