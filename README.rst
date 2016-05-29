====================
boilr-website
====================

Project Outline
----------------

Project Goals
'''''''''''''

Make it easy to generate new website repositories with the most modern build tool configurations.

Similar Work
''''''''''''

- https://github.com/google/web-starter-kit

Justification
'''''''''''''

The Google website generator has too much complexity for me at this stage, and I like to be able to control my build tools.


Summary
'''''''

============= ==============
License       Language
------------- --------------
MIT           en-AU [lang]_
============= ==============

Installation
-------------

.. Code:: bash

  $ boilr template download littlemanco/boilr-website

Usage
-----

Swap `foo` and `bar` for your own values.

.. Code:: bash

  $ mkdir foo
  $ cd foo
  $ git init
  $ git remote add origin git@github.com:foo/bar.git
  $ boilr template use boilr-website
  $ git add .
  $ git commit -m "Initial Commit"
  $ git push

Tools
-----

Generally speaking, this presumes you'll have tools installed globally. However, configuration is included for the following tools:

- eslint http://eslint.org/

Thanks
------

- The team behind boilr (https://github.com/tmrts/boilr)

Contributing
------------

Contributions are always welcome! Nothing is to small, and the best place to start is to open an issue.

References
-----------

.. [lang] Lingoes.net,. (2015). Language Code Table. Retrieved 4 June 2015, from http://www.lingoes.net/en/translator/langcode.htm
