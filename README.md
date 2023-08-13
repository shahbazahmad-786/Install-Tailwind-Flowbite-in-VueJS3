# [Install Tailwind-Flowbite in VueJS3](https://flowbite.com)

**_*After Installing the `Tailwind-CSS` in Your Project*_**

## Install Using NPM

**_Save `Flowbite` File_**

```bash
npm install flowbite
```

---

## Change in tailwind.config.js

**_Require `Flowbite` as a plugin inside your `tailwind.config.js` file_**

```js
module.exports = {
  plugins: [require("flowbite/plugin")],
};
```

**_Additionally to your own content data you should add `flowbite` to apply the classes from the interactive elements in the `tailwind.config.js` file_**

```js
module.exports = {
  content: ["./node_modules/flowbite/**/*.js"],
};
```

---

## Flowbite components

**_Copy all components from `Flowbite` Site_**

```html
<template>
  <button
    type="button"
    class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
  >
    Flowbite Button
  </button>
</template>
```

[Browse Flowbite Site](https://flowbite.com)
