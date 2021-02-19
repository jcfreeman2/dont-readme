# This Is the Header for the Project's Main Page

Here I talk about what this project is good for and how to use it

[Here I link to another page in the project](compiling_and_running.md)

And here's how you would build a project's documentation in Sphinx (hat tip to https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html):

* Create a docs/ subdirectory for your project and cd into it
* Run `sphinx-quickstart`. Go for the option where the source and build directories are separate
* Add `'recommonmark'` to the extensions list in `source/conf.py` for markdown documents to be recognized
* Add `./build` to your repo's `.gitignore` file
* Add the names of your markdown files to `index.rst`, with relative paths but minux extensions, as described in the link above
* Run `make html`

