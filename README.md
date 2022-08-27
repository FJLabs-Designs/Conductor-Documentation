# Conductor Documentation

**[View the docs →](https://conductor.fjlaboratories.com/)**

[Contribute to the docs](https://github.com/fjlabs-designs/conductor-documentation/blob/main/CONTRIBUTING.md)

## Setup

You must have [Jekyll](https://jekyllrb.com/) installed on your system before working with this repository. Most operating systems are supported by Jekyll – follow the relevant [Install Jekyll](https://jekyllrb.com/docs/installation/) instructions for your operating system.

> **Important:** This project is built with Jekyll version 3.9.2. Older versions of Jekyll have not been tested and Jekyll 4+ is currently not supported.

## Development

When making changes to the site, including any content changes, you may run a local development server by running the following command:

```sh
$ bundler exec jekyll serve
```

This spawns a server that will be accessible via `http://localhost:4000` in your browser. Additionally, any changes made within the project – including `_post/**` changes – will automatically trigger a rebuild of the site. However, to preview the changed on your browser, you will need to manually refresh the page.

## Deployment

Our docs are deployed using [Cloudflare Pages](https://pages.cloudflare.com). Every commit pushed to `main` will automatically deploy to [conductor.fjlaboratories.com](https://conductor.fjlaboratories.com), and any pull requests opened will have a corresponding staging URL available in the pull request comments.

## License and Legal Notices

Except as otherwise noted, FJLaboratories, FJLabs-Designs, and any contributors grant you a license to the FJLaboratories Conductor Documentation and other content in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode), see the [LICENSE file](https://github.com/fjlabs-designs/conductor-documentation/blob/main/LICENSE), and grant you a license to any code in the repository under the [MIT License](https://opensource.org/licenses/MIT), see the [LICENSE-CODE file](https://github.com/fjlabs-designs/conductor-documentation/blob/main/LICENSE-CODE).