# Iris & Gian Luca Wedding Site

## Overview

This repository contains the source code for our wedding website built with **Ruby Jekyll** and deployed via **GitLab Pages**. The site includes a multilingual feature powered by a **Google Translate JavaScript widget** embedded in the footer.

## Features

* **Static site generation** with Jekyll
* **Continuous deployment** on GitLab Pages
* **Google Translate integration** for multilingual accessibility
* **Responsive layout** for desktop and mobile devices
* **Simple decorative layout** with four PNG images positioned at the site’s corners for a festive wedding feel

## Prerequisites

* [Ruby](https://www.ruby-lang.org/) (version 2.7 or later recommended)
* [Bundler](https://bundler.io/)
* [Jekyll](https://jekyllrb.com/)
* GitLab account with Pages enabled

## Installation

1. Clone the repository:

   ```bash
   git clone https://gitlab.com/gfiasco88/iris-gianluca.git
   cd iris-gianluca
   ```

2. Install dependencies:

   ```bash
   bundle install
   ```

3. Build and serve locally:

   ```bash
   bundle exec jekyll serve
   ```

   The site will be available at `http://localhost:4000`.

## Deployment

Deployment is handled automatically via **GitLab CI/CD** using the `.gitlab-ci.yml` configuration provided in this repository.

Each commit pushed to the default branch will trigger a new build and deploy the site to GitLab Pages.

## Google Translate Integration

The site includes a JavaScript widget in the footer that enables visitors to translate the website into different languages using **Google Translate**.

Example snippet:

```html
<div id="google_translate_element"></div>
<script type="text/javascript">
  function googleTranslateElementInit() {
    new google.translate.TranslateElement({pageLanguage: 'en'}, 'google_translate_element');
  }
</script>
<script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
```

## Decorative Layout

The wedding site uses a simple layout with **four PNG images** placed at each corner of the page. These add a celebratory touch to the design. If this design fits your own wedding (or any event) needs, feel free to copy or adapt the structure.

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit (`git commit -m 'Add new feature'`)
5. Push (`git push origin feature-branch`)
6. Open a merge request on GitLab

## License

This project is licensed under the [MIT License](LICENSE).
