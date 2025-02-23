
This is a React with [Next.js](https://nextjs.org) project developed during Rocketseat's NLW Connect in 2025.

## Getting Started

### Prepare development environment:

-  Install node version manager
-  Install nodejs version 22
-  Install VS Code

settings.json:
-  terminal.integrated.fontSize: 14
-  explorer.compactFolders: false

### Install VS Code extensions:
-  Tailwind CSS IntelliSense
-  Omni Theme
-  Symbols
-  PostCSS Language Support
-  Biome

### Create and run [Next.js](https://nextjs.org/docs/app/getting-started/installation) project:

```bash
-  npx  create-next-app@latest  --empty
-  npm  run  dev
```

### Set up [Tailwind](https://tailwindcss.com/docs/installation/framework-guides/nextjs) CSS:

- Install TailWind
```bash
npm  install  tailwindcss  @tailwindcss/postcss  postcss
```
-  Create a  postcss.config.mjs file in the root of your project and add the @tailwindcss/postcss plugin to your PostCSS configuration.
-  Add an @import to ./src/app/globals.css that imports Tailwind  CSS
-  Import './globals.css' in the layout.tsx file.

### Set up [Biome](https://biomejs.dev/guides/getting-started/):
 - Install Biome
```bash
 # install as development dependency
npm  install  @biomejs/biome -D
npx  @biomejs/biome  init
```
 - Open Workspace Setting (Json)
    - Enable Biome for languages javascript, typescript and typescriptreact by adding:
	   - "editor.defaultFormatter":  "biomejs.biome"
	- Enable  fix  on  save  by  adding:
	   -  "source.fixAll.biome":  "explicit"
	   - "source.organizeImports.biome":  "explicit"
	-  Enable  format  on  save  by  adding:
		- "editor.formatOnSave":  true

### Install other packages:
 - Install [Lucide Icons](https://lucide.dev/icons/) (Icon toolkit)
 ```bash
npm install lucide-react
```
 - Install [Tailwind Merge](https://www.npmjs.com/package/tailwind-merge) (Tailwind class merger)
 ```bash
npm install tailwind-merge 
```
 - Install [React Hook Form](https://www.react-hook-form.com/) (Form management library)
 ```bash
npm install react-hook-form
```
 - Install [Zod](https://zod.dev/) with Hook Form integration (Schema validation library)
 ```bash
npm install zod @hookform/resolvers
```
 - Install [Orval](https://orval.dev/overview) (API client generator)
 ```bash
 # install as development dependency
npm install orval -D 
```