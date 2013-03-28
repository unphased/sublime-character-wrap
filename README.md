sublime-character-wrap
===============

Extension for Sublime Text that allows quick modification of wrapping characters. 

The idea is to give control over performing the opposite action to typing any of the "wrapping characters" (`{[('"`), thereby making it possible to quickly switch the wrapping characters without manually doing something twice. 

Features

1. A key that is very similar to but slightly different from `ctrl+shift+m` which will search out to matching characters and select the block contained within (probably also including the wrapper characters)
2. Entering a wrapping character whenever the selection begins and terminates with matching wrapping characters causes those wrapping characters in the selection to be replaced by the character typed

I have put this on hold upon the discovery of this excellent plugin which efficently handles the case for flipping between single and double quotes using one keychord: https://github.com/spadgos/sublime-ToggleQuotes
