# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Setup instructions](#setup-instructions)

## Overview

### Screenshot

![Desktop Design](screenshots/desktop-design.png)

![Mobile Design](screenshots/mobile-design.png)

### Links

- Solution URL: [https://github.com/kkarad/qr-component](https://github.com/kkarad/qr-component)
- Live Site URL: [https://kkarad-qr-component.netlify.app/](https://kkarad-qr-component.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Tailwind CSS
- Flexbox
- Mobile-first workflow
- [Vite](https://vitejs.dev/) - For building and serving the project
- [Google Fonts](https://fonts.google.com/) - For the fonts

### What I learned

I learned how to use: 

* Tailwind CSS with Vite
* Flexbox to position elements on the page
* the Mobile-first workflow
* Google Fonts

### Useful resources

- [YouTube Video](https://www.youtube.com/watch?v=sOnBG2wUm1s) - This video tutorial helped me to setup google fonts with Tailwind CSS.concept.

## Author

- Website - [@kkarad](https://github.com/kkarad)
- Frontend Mentor - [@kkarad](https://www.frontendmentor.io/profile/kkarad)
- Twitter - [@kkarad](https://www.twitter.com/kkarad)

## Setup instructions

Initialize project

```
npm init
npm install --save-dev vite
cat <<- EOF > vite.config.ts
import { defineConfig } from 'vite'

export default defineConfig({
  // ...
})
EOF
```

Add to package.json

```
"scripts": {
  "dev": "vite",
  "build": "vite build",
  "preview": "vite preview"
}
```

Install Tailwind CSS

```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

In tailwind.config.cjs, add the following:

```
content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
```

Initialise main css file

```
cat <<- EOF > index.css
@tailwind base;
@tailwind components;
@tailwind utilities;
EOF
```

Create .gitignore

```
cat <<- EOF > .gitignore
node_modules/
.idea/
EOF
```

Initialise git repository

```
git init
git add .
git commit -m "initial commit"
git branch -M master
git remote add origin <<your-git-repo-url>>
git push -u origin master
```
