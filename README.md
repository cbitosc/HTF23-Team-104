<<<<<<< HEAD
# HTF23-Team-104

## GitHub submission guide

In this Readme, you will find a guide on how to fork this Repository, add files to it, and make a pull request to contribute your changes.

<details open>
<summary><h3>1. Login to your GitHub Account by heading over to <a href="https://github.com">github.com</a></h3></summary>
<br>
<ul>
   <li>Open the <a href="https://github.com/cbitosc/HTF23-Team-104">current repo</a> in a new tab.</li>
   <li>Perform all operations in the newly opened tab, and follow the current tab for instructions.</li>
</ul>
</details>

<details>
<summary><h3>2. Fork the Repository</h3></summary>
<br>
<ul>
 <li>In the newly opened tab, on the top-right corner, click on <b>Fork</b></li>
 <img src="/images/fork.png">

 <li>Enter the <b>Repository Name</b> as <b>HTF23-Team-104 (your team number)</b>.</li>
 <li>Then click <b>Create Fork</b> leaving all other fields to their default value.</li>
 <img src="/images/create-fork.png">
 <li>After a few moments, you can view the repo.</li>
</ul>
</details>

<details>
<summary><h3>3. Clone your Repository</h3></summary>
<br>
<ul>
 <li>Click on <b>Code</b> and from the dropdown menu copy your <b>web URL</b> in your forked Repository. </li>
 <img src="/images/clone1.png">
 <li>Now open terminal on your local machine.</li>
 <li>Use the following command to clone your forked Repository:</li>
<code> git clone https://github.com/your-username/HTF23-Team-104.git </code>
<hr>
 <img src="/images/clone2.png">

</ul>
</details>

<details>
<summary><h3>4. Adding files to the Repository</h3></summary>
<br/>
<ul>
 <li>While doing it for the first time, create a new branch for your changes.</li>
   <code> git checkout -b branch-name </code>
   <li>Add your files or make modifications to existing files.</li>
   <li>Stage your changes:</li>
   <code> git add . </code>
   <li>Commit your changes:</li>
   <code> git commit -m "Descriptive commit message" </code>
   <li>Push changes to your fork </li>
   <code> git push origin branch-name </code>
   <hr>
   
 <img src="/images/push.png">
</ul>
</details>

<details>
<summary><h3>5. Create a Pull Request</h3></summary>
   <br>
<ul>
 <li>Finally, click on the <b>Contribute</b> button and choose <b>Open Pull Request</b>.</li>
 <img src="/images/PR1.png">
 <li>Leaving all fields to their default values, click on <b>Create Pull Request</b>.</li>
 <img src="/images/PR2.png">
 <li>Wait for a few moments, then you are all done</li>
</ul>
</details>

## Thanks for participating!
=======
# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
>>>>>>> 75dfaf8 (files added)
