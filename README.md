Notes
=====

Notes, documents and other kind of texts. For now I'll be adding my notes for
the last two subjects of my MSc studies.

## Compiling LaTeX

The notes have been written using LaTeX on Linux Mint. If you don't want to
deal with dependencies and have **plenty** of HD space, just use:

    sudo apt-get install texlive-full

Also, you need [Pygments](http://pygments.org/) for the code highlighting. It can be easily installed using:
  
    sudo pip install pygments

Or, if you're using a debian-based system, you can use the apt package manager:

    sudo apt-get install python-pygments

Once you have all the dependencies, just run

    make

And the `pdf` file will be generated in the same folder.
