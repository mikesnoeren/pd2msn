# PD2MSN
The official PD2MSN repository.

**Please keep the following in mind:**
- This repository has [no license](https://choosealicense.com/no-permission/), which means the work is under exclusive copyright. Nobody can copy, distribute or modify my work without being at risk of take-downs, shake-downs or litigation.
- This repository makes use of [TailwindUI](https://tailwindui.com/), which requires a paid licensed to use.

This repository is based on the [mikesnoeren/craft](https://github.com/mikesnoeren/craft) repository, which is an Craft CMS 4 scaffolding project using Tailwind and Alpine. If you want to use that repository please do not hestate to do so. For simplicity's sake I have added it's entire `README.md` below.

<hr>

# About mikesnoeren/craft

This repository was created to provide an easy starting point for your new [Craft CMS 4](https://github.com/craftcms/cms) projects.

Please be aware that this project is very opinionated; it expects you to mostly be using [TailwindCSS](https://github.com/tailwindlabs/tailwindcss) and [Alpine.js](https://github.com/alpinejs/alpine) for the frontend.
If you do require custom JavaScript or CSS, it will be bundled, transformed and minified using [vite](https://github.com/vitejs/vite) and [PostCSS](https://github.com/postcss/postcss).

## Using mikesnoeren/craft
The setup assumes you use [ddev](https://github.com/drud/ddev), if you use an alternative development environment, please change the steps below accordingly.

### 1. Clone this project by clicking [here](https://github.com/mikesnoeren/craft/generate)

### 2. Run the project: `ddev start && ddev exec npm run watch`