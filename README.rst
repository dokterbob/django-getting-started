Getting started with Python/Django
==================================

This is a getting started guide for (experienced) non-Python developers who want to practise Django on a professional level. It basically is an overview of basic resources for acquiring the relevant skills.

#. Get acquinted with a decent text editor:

   * `Sublime Text <http://www.sublimetext.com/>`_
   * `VIM <http://tips.webdesign10.com/vim-tutorial>`_
   * `Emacs <http://www.linuxjournal.com/article/6242>`_

#. Make sure your editor is configured to behave nicely with regards to
   indentation and whitespace, for Python and modern DCVS this *is* important:

   - PEP8 related
      * Use 4 `spaces for indentation <http://www.python.org/dev/peps/pep-0008/#tabs-or-spaces>`_ (not tabs).
      * Make sure your editor forces a `limited line length <http://www.python.org/dev/peps/pep-0008/#maximum-line-length>`_ of 79 characters.

   - DCVS related
      * Automatically `remove trailing whitespace <http://codeimpossible.com/2012/04/02/Trailing-whitespace-is-evil-Don-t-commit-evil-into-your-repo-/>`_ in order to work well with DCVS.
      * Assure there is a `newline at the end of each file <http://unix.stackexchange.com/questions/18743/whats-the-point-in-adding-a-new-line-to-the-end-of-a-file>`_.

   For Sublime Text these settings amount to the following configuration lines::

    "trim_trailing_white_space_on_save": true,
    "translate_tabs_to_spaces": true,
    "rulers": [78],
    "ensure_newline_at_eof_on_save": true

#. Install Python by following the excellent installation instructions from
   `The Hitchhiker’s Guide to Python! <http://docs.python-guide.org/en/latest/index.html>`_ (DON'T PANIC!).

#. For learning Python, once again, `The Hitchhiker’s Guide <http://docs.python-guide.org/en/latest/intro/learning/>`_
   is the way to go. Also, we can recommend having O'Reilly's
   `Python Pocket Reference <http://search.oreilly.com/?q=Python+Pocket+Reference>`_
   at hand during initial steps of Python programming.

#. Read the excellent `Getting Started <https://docs.djangoproject.com/en/dev/intro/>`_ manual
   supplied with the Django documentation. and make sure to work through all of the
   parts of the 'Writing your first Django app'.

#. Getting started with Distributed Version Control Systems (DCVS):

   * `GIT <http://git-scm.com/>`_ and `GitHub <https://www.github.com/>`_
       - Mac
           * `Getting started with GitHub on Mac <http://help.github.com/mac-set-up-git/>`_
           * `GitHub for Mac <http://mac.github.com/>`_ for beginners
           * `GitX <https://github.com/brotherbard/gitx/zipball/v0.7.1>`_, `Tower <http://www.git-tower.com/>`_ or `SourceTree <http://www.sourcetreeapp.com/>`_ for advanced users
       - Windows
           * `Getting started with GitHub on Windows <https://help.github.com/articles/getting-started-with-github-for-windows>`_
           * `GitHub for Windows <http://windows.github.com/>`_ for beginners
           * `SourceTree <http://www.sourcetreeapp.com/>`_ for advanced users
       - Command line tools
           * `git diff`
           * `git checkout`
           * `git push`, `git pull`
           * `Branching and merging <http://gitref.org/branching/>`_
           * `git mergetool`

   * `Mercurial <http://mercurial.selenic.com/>`_ / `Bitbucket <https://bitbucket.org/>`_

#. Now you are ready to study Django and Python's best practises, many of which
   have been documented in Daniel Greenfeld and Audrey Roy's awesome book
   `Two Scoops of Django <https://django.2scoops.org/>`_.

   Buy this book. Take it with you wherever you go. Leave it under your pillow
   as you sleep.

#. Study basic (modern) web development:

   * `HTML5 / CSS3 <http://diveintohtml5.info/>`_
   * `jQuery / JS <http://docs.jquery.com/Tutorials:Getting_Started_with_jQuery>`_

#. Get acquinted with Python package structure best practises:

   * `The Hitchhiker’s Guide to Packaging <http://guide.python-distribute.org/>`_

#. Get acquinted with deployment practises for production environments:

   * Running a Django server with `gunicorn <http://gunicorn.org/>`_
   * Front end webhosting `Lighttpd <http://www.lighttpd.net/>`_ / `NGinx <http://www.nginx.org/>`_
   * Serving static files using `Amazon CloudFront <http://aws.amazon.com/cloudfront/>`_

   * Sending email using `Sendgrid <http://sendgrid.com/>`_
   * Continuous testing and integration with `Jenkins <https://sites.google.com/site/kmmbvnr/home/django-jenkins-tutorial>`_
   * Deployment and administration automation with `Fabric <http://readthedocs.org/docs/fabric/en/latest/index.html>`_
