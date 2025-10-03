# Obsidian Plugin Template

A template for creating [Obsidian](https://obsidian.md) plugins using **TypeScript** and **esbuild**.
This provides a minimal setup to get started quickly with your own plugin development.

## Project Structure

```
.
├── src
│  └── main.ts
├── esbuild.config.mjs
├── .gitignore
├── LICENSE
├── manifest.json
├── package-lock.json
├── package.json
├── README.md
├── styles.css
└── tsconfig.json
```

## Getting Started

### 1. Install dependencies

```bash
npm install
```

### 2. Build the plugin

```bash
npm run build
```

(For development with automatic rebuilds:)

```bash
npm run dev
```

### 3. Load into Obsidian

1. Build the plugin (generates `main.js`).
2. Copy or symlink the plugin folder into your Obsidian vault under:

   ```
   <your-vault>/.obsidian/plugins/
   ```
3. Open Obsidian → **Settings → Community Plugins** → Enable this plugin.

## License

This project is licensed under the [MIT License](./LICENSE).
