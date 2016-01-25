## My Default Atom Installation

0. Completely remove old Installation
```
rm ~/.atom
rm /usr/local/bin/atom
rm /usr/local/bin/apm
rm /Applications/Atom.app
rm ~/Library/Preferences/com.github.atom.plist
rm ~/Library/Application Support/com.github.atom*
rm ~/Library/Application Support/Atom
rm ~/Library/Saved Application State/com.github.atom*
rm ~/Library/Caches/com.github.atom
rm ~/Library/Caches/Atom
```
1. Download and install [Atom](http://atom.io)
2. Atom > Install Shell Commands
3. Install plugins
```
apm install Sublime-Style-Column-Selection csscomb cssnano language-babel language-ejs language-javascript-jsx language-twig linter linter-js-standard linter-sass-lint linter-jsonlint linter-tidy monokai standard-formatter tabs-to-spaces tree-view-git-modified
```
4. Copy included config.cson over ~/.atom/config.cson
5. Place various . files at root of project.
