Sublime Text 2 & 3 tools for Macaroni
=====================================

How to install:
---------------
Find the directory where Sublime puts all of its packages and stuff. In many versions of Sublime, you can just click on "Preferences" followed by "Browse Packages" and it will open the directory up for you.

Open up a terminal (or command prompt) and cd into this directory and clone this project:

git clone https://github.com/TimSimpson/Sublime-Macaroni.git Macaroni

Now back in Sublime Text, open a "mcpp" file. Click on "View", then "Syntax" and click on the "Macaroni" option which will have just appeared.


What's it Do
------------
Makes syntax look prettier.

It also lets you invoke Macaroni to build stuff, although in most cases you'll probably want to tweak it to do what you need for your own project. To build you'll need to have macaroni in your $PATH (or %PATH% if you prefer), along with anything Macaroni might invoke to actually build the project. Right now the regular expressions look for output coming from MSVC++, not GNU. I'll have to add that soon.

To use, in Sublime click "Tools", then "Build System", and select either Macaroni-GCC or Macaroni-MSVC.
