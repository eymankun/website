# Aiman CV

Curriculum Vitae of Muhammad Aiman. Created with mkdocs.

[![build-and-deploy](https://github.com/eymankun/website/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/eymankun/website/actions/workflows/main.yml)

## Installation

### with `pip`

Use `pip` to install all required packages inside `requirements.txt`, ideally by using a virtual environment. Install with:

```bash
pip install -r requirements.txt
```

## Test with a Local Site Server

Use the following command to establish a local server:

```bash
mkdocs serve
```

Then open the local site in any browser at the URL `http://127.0.0.1:8000`.

## Build Site

Build your site files with the command:

```bash
mkdocs build
```

Site files will be inside the `site` directory. Deploy the contents of the `site` to web server.

## Deploy to Github Pages

If this code is in Github, Github Pages is the most convenient way to publish this site. Use the following command to deploy:

```bash
mkdocs gh-deploy --config-file path/to/mkdocs.yml --force
```
