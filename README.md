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
apm install Sublime-Style-Column-Selection csscomb cssnano language-babel language-ejs language-javascript-jsx language-twig linter linter-js-standard linter-scss-lint linter-jsonlint linter-tidy monokai standard-formatter tabs-to-spaces tree-view-git-modified
```
5. Copy included config.cson over ~/.atom/config.cson, replacing paths with correct ones:
  `which scss-lint` gets scss-lint path, etc.

6. Place various . files (.scss-lint.yml, .csscomb.json, etc) at root of project.

> Packages Installed:
- Stylus@3.1.0
- Sublime-Style-Column-Selection@1.7.2
- atom-beautify@0.29.17
- atom-htmltidy@5.1.0
- atom-pair@2.0.10
- csscomb@0.3.1
- cssnano@1.1.0
- formatter@2.12.3
- formatter-tidy@1.0.1
- git-time-machine@1.5.4
- language-babel@2.53.0
- language-ejs@0.4.0
- language-javascript-jsx@0.3.7
- language-twig@1.6.3
- linter@1.11.21
- linter-eslint@8.1.0
- linter-js-standard@3.8.0
- linter-jsonlint@1.3.0
- linter-scss-lint@3.0.4
- linter-stylint@2.2.6
- linter-tidy@2.3.0
- monokai@0.20.0
- npm-install@4.0.3
- perfectionist@1.3.0
- pigments@0.39.0
- seti-ui@1.6.0
- sort-lines@0.14.0
- standard-formatter@2.8.0
- tabs-to-spaces@1.0.3
- tree-view-git-modified@0.7.1
