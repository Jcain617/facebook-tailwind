### Facebook Project

- create a new repo in Github for Facebook
- initialize the new folder
- make a new index.html file

---

issue #1: install node.js
nodejs.org
LTS version

issue #2: install yarn
- npm install --global yarn


issue #3: install tailwindcss 1.
- Install tailwindcss via npm, and create your tailwind.config.js file.
- ```bash
npm install -D tailwindcss
npx tailwindcss init
```


issue #3: push to github

crearte a repo on github
name it facebook-tailwind
copy git link 




issue #4: Configure your template paths
Add the paths to all of your template files in your tailwind.config.js file.
```js
/** @type {import('tailwindcss').Config} \*/
module.exports = {
content: ["./src/**/\*.{html,js}"],
theme: {
extend: {},
},
plugins: [],
}

```

```
