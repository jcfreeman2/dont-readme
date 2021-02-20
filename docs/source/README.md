# This Is the Header for the Project's Main Page

Here I talk about what this project is good for and how to use it

[Here I link to another page in the project](compiling_and_running.md)

And here's how you would build a project's documentation in Sphinx (hat tip to [Sphinx documentation on the ReadTheDocs website](https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html):

* Create a `docs/` subdirectory for your project and cd into it
* Run `sphinx-quickstart`. Go for the option where the source and build directories are separate
* Add `'recommonmark'` to the extensions list in `source/conf.py` for markdown documents to be recognized
* Add `build/` to a `.gitignore` file in the base of your repo
* Add the names of your markdown files in `docs/source/` to `docs/source/index.rst`, with relative paths but minus extensions, as described in the link above
* Run `make html`

