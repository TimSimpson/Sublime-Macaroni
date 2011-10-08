Sublime Text 2 tools for Macaroni
=================================

How to install:
---------------
Find the directory where Sublime puts all of its packages and stuff. In Vista, its %USERPROFILE%\AppData\Roaming\Sublime Text 2.

Put Macaroni.tmLanguage into the packages/C++ directory. This is a copy of the C++ language file with some small changes.

Put Macaroni.sublime-settings and Macaroni.sublime-build into Packages/User.

NOTE: To build you'll need to have macaroni in your %PATH%, along with anything Macaroni might invoke to actually build the project. Right now the regular expressions look for output coming from MSVC++, not GNU. I'll have to add that soon.
