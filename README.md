# RegMonkey Python Template

This repository contains a template for creating Python projects using RegMonkey.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

RegMonkey Python Template is a starting point for creating Python projects that utilize RegMonkey, a powerful library for monkey patching and dynamic code modification.

<strong > &#9654;&nbsp; GitHub Template</strong>

- To create a template repository, you must create a repository, then make the repository a template
- GitHub template repository cannot include files stored using Git LFS
- In order to set up a new template, go to your github repository, select **Settings**, and select **Template repository**

## Setup

1. Create Property. This should be aligned with the repository name
2. write the GA4 tag, e.g., `G-LCHP8F033K`, in the `quarto.yml`
3. Go to Google Search Console and register the quarto page url

## Publish

<strong > &#9654;&nbsp; Task List at GitHub Repository Push</strong>

- [ ] export poetry managed packages into `requirements.txt`

```zsh
% cd <repository root>
% poetry export --without-hashes --format=requirements.txt --output requirements.txt --with quarto_env
```

<strong > &#9654;&nbsp; Publish by quarto command</strong>

first need to run

```zsh
% quarto publish gh-pages
```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
