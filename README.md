# cic-av-manual
Columbus Italian Club AV Manual

#To render the manual
In zsh

#first time
brew install pandoc
pandoc --version

#render markdown
pandoc index.md sections/*.md -s --toc -o manual.html
open manual.html
