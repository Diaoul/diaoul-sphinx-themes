Diaoul Sphinx Styles
====================

This repository contains sphinx styles Diaoul uses in most of his projects.
It is a derivative of Mitsuhiko's themes for Flask and Flask related projects.
To use this style in your Sphinx documentation, follow this guide:

1. Put this folder as _themes into your docs folder.  Alternatively
   you can also use git submodules to check out the contents there.

2. Add this to your conf.py::

    sys.path.append(os.path.abspath('_themes'))
    html_theme_path = ['_themes']
    html_theme = 'diaoul'

The following theme options exist:

* ``github_user``: GitHub user or organization name
* ``github_repo``: GitHub repository name
* ``github_branch``: GitHub repository branch
* ``fork_me``: set to 1 to use the "Fork Me" badge
* ``flattr``: set to 1 to enable Flattr
* ``flattr_href``: website for Flattr
* ``flattr_thing_url``: thing URL for Flattr
* ``gittip``: set to 1 to enable Gittip
* ``pypi_downloads``: set to 1 to enable the PyPI downloads badge
* ``pypi_version``: set to 1 to enable the PyPI version badge
* ``travis``: set to 1 to enable the Travis-CI build badge
* ``coveralls``: set to 1 to enable the Coveralls coverage badge
