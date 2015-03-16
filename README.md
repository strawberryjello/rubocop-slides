# rubocop-slides

A quick intro to [Rubocop](https://github.com/bbatsov/rubocop).

Exporting the Org file to an S5 presentation requires Org 8.0 or higher. To install the latest version of Org, see the [Org manual installation instructions](http://orgmode.org/manual/Installation.html). For older versions of Org, try [org-s5](https://github.com/eschulte/org-S5). The ui directory is taken from org-s5, which contains the default, i18n, and railscast themes.

To export (Org 8.0 and up):
- add the Org directory to your load path if you installed Org manually
- add the Org contrib/lisp/ directory to your load path
- require ox-s5 in your .emacs/init.el
- in your Org file, run org-s5-export-as-html
- put the generated HTML file in the same directory as the ui directory
- to change themes, replace the path to ui/default/slides.css with the path to the slides.css from one of the other themes
