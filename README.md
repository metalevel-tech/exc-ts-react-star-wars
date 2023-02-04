# SWAPI Search App with ReactJs and TypeScript

SWAPI (Star Wars API) Search App with ReactJs and Typescript Exercise.

## Resources and referens

- [Star Wars API](https://swapi.dev/)

  Related:

  - [SW Guide Site](https://starwars-visualguide.com/)
  - [SW Guide GitHub](https://github.com/tbone849/star-wars-guide/tree/master/build/assets/img)
  - [SWAPI Json Server GitHub](https://github.com/johnlindquist/swapi-json-server/tree/master/public)
  - <https://swapi.py4e.com/about>
  - <https://starwars.fandom.com/wiki/Obi-Wan_Kenobi_(television_series)>

- [Star Jedi Font](https://www.dafont.com/star-jedi.font)

- [Font Converter](https://cloudconvert.com/ttf-converter)

## Setup the Project

<details>

### Install ReactJs and Typescript by [Vite](https://vitejs.dev/guide/why.html)

```bash
npm create vite@latest
# ✔ Project name: … exc-ts-react-star-wars
# ✔ Select a framework: › React
# ✔ Select a variant: › TypeScript
cd exc-ts-react-star-wars/
npm install
npm i react-router-dom axios dompurify @types/dompurify
```

- Create start command in [`package.json`](package.json) file as follows:

  ```json
  "scripts": {
      "start": "vite --host 0.0.0.0 --port 3000",
  }
  ```

- Clean the `src/` and `public/` directories and start working on the project.

### Install other packages

```bash
npm i --save-dev tailwindcss postcss autoprefixer postcss-import
npx tailwindcss init -p
```

```bash
npm i @tailwindcss/forms @tailwindcss/typography @tailwindcss/aspect-ratio
npm i @headlessui/react
npm i @heroicons/react
npm i react-icons
```

**References:**

- <https://tailwindui.com/>
- <https://react-icons.github.io/react-icons/>
- <https://headlessui.com/>
- <https://heroicons.com/>

### Setup the Git Repository and Push to GitHub

```bash
# git config --global init.defaultBranch master
git init
git add -A
git commit -m "Initial commit"
git branch -M master
git remote add origin git@github.com:metalevel-tech/exc-ts-react-star-wars.git
git push -u origin master
```

### Automation with GitHub Actions

- [Deploy to GitHub Pages and Automate with GitHub Actions](https://github.com/metalevel-tech/exc-js-react-tic-tac-toe#deploy-to-github-pages-with-github-actions)

</details>
