## My Default Atom Installation

0. Completely remove old Installation:
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

1. Install linters:
```
npm i -g semistandard
gem install scss-lint
```

2. Download and install [Atom](http://atom.io)
3. Atom > Install Shell Commands
4. Install plugins
```
apm install Sublime-Style-Column-Selection csscomb cssnano language-babel language-ejs language-javascript-jsx language-twig linter linter-js-standard linter-sass-lint linter-jsonlint linter-tidy monokai standard-formatter tabs-to-spaces tree-view-git-modified
```
5. Copy included config.cson over ~/.atom/config.cson, replacing paths with correct ones:
  `which scss-lint` gets scss-lint path, etc.

6. Place various . files (.scss-lint.yml, .csscomb.json, etc) at root of project.

> Packages Installed:
-  Sublime-Style-Column-Selection@1.5.1
-  csscomb@0.3.1
-  cssnano@1.1.0
-  language-babel@2.14.1
-  language-ejs@0.2.0
-  language-javascript-jsx@0.3.7
-  language-twig@1.6.2
-  linter@1.11.3
-  linter-js-standard@3.2.1
-  linter-jsonlint@1.1.4
-  linter-sass-lint@1.0.1
-  linter-tidy@2.1.0
-  monokai@0.18.0
-  standard-formatter@2.0.0
-  tabs-to-spaces@1.0.1
-  tree-view-git-modified@0.6.2
