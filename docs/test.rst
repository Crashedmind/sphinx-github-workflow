======================================================
Github
======================================================

A website, documentation, or other information in github can be hosted on https://pages.github.com/.

See https://help.github.com/en/articles/about-github-pages.

.. tip ::

    Sphinx output HTML can be hosted on https://pages.github.com/. 

    https://sphinx-gallery.github.io/index.html is a good example.


.. warning ::

    For Sphinx generated html to render, an empty file called ``.nojekyll`` must be added to the root directory. 

    This tells GitHub Pages not to run the published files through Jekyll. This is important since Jekyll will discard any files that begin with ``_``. 
    
    In the case of Sphinx, this would be the _images/  _sources/ _static/ directories!
