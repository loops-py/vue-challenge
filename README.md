# vue-challenge

Use the following API [https://openlibrary.org/dev/docs/api/search] to create a simple web app that includes:

## Pages

- A `search page` that allows users to search for books by title, author, or subject.

- A `list of books page` that displays a list of books after searching. (books should also a favourite button that sets them as favourite throughout a local vuex module of favuorites)

- A `book page` that displays the details of a book after clicking on a book in the book list page. (books should also a favourite button that sets them as favourite throughout a local vuex module of favuorites)

- A `favorite books page` that displays a list of favorite books.

*You can use anyting you like for the API, but make sure to use the search API as well as axios.*

You have a starter nuxt template repo in here, and you are able to make any changes that you want.
But please consider the following:

- Tailwind.css has been installed and should be used as a default means of styling.
- The axios actions should be called from a vuex store and the data should be handled by a vuex module.
- Try making the app responsive is plausible.
- The app should be able to handle errors (even if its just `console.error`).
- The styling of the page is not the most important part of the project, but how the diff frameworks are used in the app and how clean/managed your code is.
- This is a code challenge not a design one, so feel free to add as many or as little detail as you like as long as the
page flows work and the data is handled correctly.


Fork this repo and work on you own repo as that would be the repo we will be reviewing.

GOOD LUCK!

## Create project

```bash
# create project
npx nuxi@latest init <project-name>

# Install Axios, Pinia, Tailwind.css, Prettier and ESlint and configurate all
```

For detailed explanation on how things work, check out the [documentation](https://nuxtjs.org).

## Special Directories

You can create the following extra directories, some of which have special behaviors. Only `pages` is required; you can delete them if you don't want to use their functionality.

### `assets`

The assets directory contains your uncompiled assets such as Stylus or Sass files, images, or fonts.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/assets).

### `components`

The components directory contains your Vue.js components. Components make up the different parts of your page and can be reused and imported into your pages, layouts and even other components.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/components).

### `layouts`

Layouts are a great help when you want to change the look and feel of your Nuxt app, whether you want to include a sidebar or have distinct layouts for mobile and desktop.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/layouts).


### `pages`

This directory contains your application views and routes. Nuxt will read all the `*.vue` files inside this directory and setup Vue Router automatically.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/get-started/routing).

### `plugins`

The plugins directory contains JavaScript plugins that you want to run before instantiating the root Vue.js Application. This is the place to add Vue plugins and to inject functions or constants. Every time you need to use `Vue.use()`, you should create a file in `plugins/` and add its path to plugins in `nuxt.config.js`.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/plugins).

### `static`

This directory contains your static files. Each file inside this directory is mapped to `/`.

Example: `/static/robots.txt` is mapped as `/robots.txt`.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/static).

### `store`

This directory contains your Vuex store files. Creating a file in this directory automatically activates Vuex.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/store).
