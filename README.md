# FinEdge-Like-Website

The website is developed using the Astro framework along with HTML, CSS, and JavaScript.

## Astro Starter Kit: Basics

```
npm create astro@latest -- --template basics
```

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
│   ├── images/
|   |   └── logo.png
|   |   └── img1.png
|   |   └── img2.png
|   |   └── img3.png
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Header.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   |   └── index.astro
│   |   └── aboutUs.astro
│   |   └── services.astro
│   |   └── contactUs.astro
|   └── styles/
│       └── style.css
│       └── bg1.jpg
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.


### Navigation Bar

The navigation bar provides links to the following sections:

- Home
- About Us
- Services
- Contact Us

### Home Section

- The home section is an attractive landing section with a catchy headline and a brief description of "FinEdge".

### About Us Section

- The about us section provides a brief background about "FinEdge" based on the description given above.

### Services Section

- The services section displays at least three different financial services that "FinEdge" offers. Each service includes a brief description and an appropriate image/icon. The services could be related to individual money transfers, business payments, and real-time tracking of payments.

### Contact Us Section

- The contact us section includes a simple contact form with fields for name, email, and a message. Please note that the form doesn't need to be functional, i.e., it doesn't need to send real emails.


## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:3000`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
