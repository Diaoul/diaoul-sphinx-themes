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
* ``fork_me``: set to 1 to use the "fork_me" badge. Require ``github_user`` and ``github_repo`` to be set
* ``flattr_href``: Website for Flattr
* ``flattr_thing_url``: Thing URL for Flattr
