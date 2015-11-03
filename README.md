# presentation-template
A barebones [reveal.js](https://github.com/hakimel/reveal.js/) deck for Deis presentations.

## Setting up

To get started, fork this repository and name it for your talk. Then, clone it
and initialize submodules:

- Clone with `--recursive`:
```
git clone ${REPO_URL} --recursive
```
OR
- Clone normally and then initialize submodules:
```
git clone ${REPO_URL}
git submodule update --init --recursive
```

## Editing

Opening `index.html` in your browser should render the presentation. Make
changes to the HTML and reload.

The document has HTML comments around blocks you'll likely want to customize.

## Presenting

Push to the `gh-pages` branch of your fork and GitHub Pages should start rendering your static presentation at your repository URL. For example: http://carmstrong.github.io/ceph-days-sf-deis-2015/
