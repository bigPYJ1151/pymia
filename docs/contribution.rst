.. _contribution:

Contribution
============

Contributors are highly welcome on all levels such as new features, improvements, bug fixes, and documentation.
Please read this chapter carefully to hold a certain standard in code quality.

Code Style
----------
We follow the `PEP 8 -- Style Guide for Python Code <https://www.python.org/dev/peps/pep-0008/>`_.

Code Documentation
------------------
Please document your code. Each package, module, class, and function should have a comment.
We use `Google style docstrings <http://google.github.io/styleguide/pyguide.html#Comments>`_, and you can find
a great example `here <http://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_google.html>`_.
For major changes, it might also be good to update the documentation you are currently reading.
It is generated with `Sphinx <http://www.sphinx-doc.org>`_, and you can find the source files in the ``./docs`` directory.

Code Tests
----------
You do write tests, don't you? They are located in the ``./test`` directory.

Commit Messages
---------------
The commit messages follow the
`AngularJS Git Commit Message Conventions <https://gist.github.com/stephenparish/9941e89d80e2bc58a153>`_
with the following format::

    <type>(<scope>): <subject>
    <BLANK LINE>
    <body>
    <BLANK LINE>
    <footer>

Usually the first line is enough, i.e. ``<type>(<scope>): <subject>`` .
It contains a succinct description of the change. Allowed ``<type>`` s are:

 * ``feat``: feature
 * ``fix``: bug fix
 * ``docs``: documentation
 * ``style``: formatting, missing semi colons, ...
 * ``refactor``
 * ``test``: when adding tests
 * ``chore``: maintain

An example would be: ``feat(metric): add Dice coefficient metric``

TODOs
-----
Mark todos like this::

    # TODO(<name>): improve performance by vectorization

Where ``<name>`` should be replaced by your GitHub name.
