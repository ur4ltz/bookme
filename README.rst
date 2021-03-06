bookme
======

A handy helper for acquiring the textbooks made `freely available by Springer`__ during Covid 19

__ https://link.springer.com/search?package=mat-covid19_textbooks&facet-content-type=%22Book%22

.. code:: console

  $ ./bookme.zsh -h
  Usage: bookme [--procs <number of simultaneous downloads>] [--format epub|pdf|both] [--folder <path>] [<textbooks.csv>]
  $ ./bookme.zsh

Just run it without arguments for interactive menus.

.. image:: https://gist.githubusercontent.com/AndydeCleyre/8fd1110b324df7d5ab84454d14f2b86e/raw/bfde8b008973c731a5149b78a917b92ba4a83628/bookme.svg?sanitize=true

Dependencies
------------

- fzf
- curl
- GNU wget
- zsh

On macOS? I recommend installing homebrew__ and running:

.. code:: console

  $ brew install fzf wget

__ https://brew.sh/
