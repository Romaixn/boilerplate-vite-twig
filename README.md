<div align="center">

  <h1>Boilerplate Vite Twig</h1>

  <p>
    Boilerplate with Twig / Bootstrap / SCSS / jQuery
  </p>


<!-- Badges -->
<p>
  <a href="https://github.com/Romaixn/boilerplate-vite-twig/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/Romaixn/boilerplate-vite-twig" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/Romaixn/boilerplate-vite-twig" alt="last update" />
  </a>
  <a href="https://github.com/Romaixn/boilerplate-vite-twig/network/members">
    <img src="https://img.shields.io/github/forks/Romaixn/boilerplate-vite-twig" alt="forks" />
  </a>
  <a href="https://github.com/Romaixn/boilerplate-vite-twig/stargazers">
    <img src="https://img.shields.io/github/stars/Romaixn/boilerplate-vite-twig" alt="stars" />
  </a>
  <a href="https://github.com/Romaixn/boilerplate-vite-twig/issues/">
    <img src="https://img.shields.io/github/issues/Romaixn/boilerplate-vite-twig" alt="open issues" />
  </a>
  <a href="https://github.com/Romaixn/boilerplate-vite-twig/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/Romaixn/boilerplate-vite-twig.svg" alt="license" />
  </a>
</p>

<h4>
    <a href="#">View Demo</a>
  <span> · </span>
    <a href="#">Documentation</a>
  <span> · </span>
    <a href="https://github.com/Romaixn/boilerplate-vite-twig/issues/">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/Romaixn/boilerplate-vite-twig/issues/">Request Feature</a>
  </h4>
</div>

<br />

<!-- Table of Contents -->
# :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  * [Features](#dart-features)
- [Getting Started](#toolbox-getting-started)
  * [Prerequisites](#bangbang-prerequisites)
  * [Run Locally](#running-run-locally)
  * [Deployment](#triangular_flag_on_post-deployment)
- [Contributing](#wave-contributing)
- [Contact](#handshake-contact)



<!-- About the Project -->
## :star2: About the Project

<!-- Features -->
### :dart: Features

- Build assets using Vite.js
- Twig support
- Bootstrap support
- jQuery support

<!-- Getting Started -->
## 	:toolbox: Getting Started

<!-- Prerequisites -->
### :bangbang: Prerequisites

This project uses Yarn as package manager

```bash
 npm install --global yarn
```

<!-- Run Locally -->
### :running: Run Locally

Clone the project

```bash
  git clone https://github.com/Romaixn/boilerplate-vite-twig.git
```

Go to the project directory

```bash
  cd boilerplate-vite-twig
```

Install dependencies

```bash
  yarn install
```

Start the server

```bash
  yarn dev
```

### How to add pages ?
#### Create the twig file
Create a twig file in the templates folder with this minimal content:
```twig
{% extends "base.html.twig" %}

{% block body %}
    Your content here
{% endblock %}
```
> The content of the page will go between the `block body` and the `endblock`

#### Create the html file
Add the page in .html format to the root of the project. (next to index.html and about.html) With this minimal content:

```html
<script type="application/json" data-template="templates/name-of-your-page.html.twig">
{
}
</script>
```

> Replace `name-of-your-page` by the name of your template

You can add any variables you want in JSON. (a list of items for use in loop, the title of the page, etc..)

#### Adding output for production build
Add your page in `vite.config.js` file in the root of the project.

<!-- Deployment -->
### :triangular_flag_on_post: Deployment

To build your assets run

```bash
  yarn build
```

<!-- Contributing -->
## :wave: Contributing

<a href="https://github.com/Romaixn/boilerplate-vite-twig/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Romaixn/boilerplate-vite-twig" />
</a>


Contributions are always welcome!

See `contributing.md` for ways to get started.

<!-- Contact -->
## :handshake: Contact

Romain Herault - [@Romaixn](https://twitter.com/romaixn)

Project Link: [https://github.com/Romaixn/boilerplate-vite-twig](https://github.com/Romaixn/boilerplate-vite-twig)
