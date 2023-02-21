# problems-ive-had
A collection of problems I've run into, some with solutions.

## Enviornment

### Terminal

* I want to know what different terminal fonts looks like.
  * [app.programmingfonts.org](https://app.programmingfonts.org/#camingocode)

### Package management

* I want a reproducible set of brew packages.
  * [brew bundle dump](https://tomlankhorst.nl/brew-bundle-restore-backup/)

## Browser

* I want to use keyboard navigation whenever possible.
    Unfinished GPT prompt:
      
      0. build a function that will do the following:
      1. when a user hovers over an element with an onclick handler, the element will be visually highlighted in some way
      2. when the visual highlight is visible, if the user presses the '!' key on the keyboard, a menu will show up and ask if the user wants to set a hotkey to activate that element.
      3. if the user say yes, then the user will be prompted to press a key combination with the 'alt' modifier, such as 'alt-a' or 'alt-5'. the user will then be notified that this choice has been remembered, which it will be. the ux described here will then go away.
      4. additionally, when the user presses the alt key on its own, small hover texts will appear over each visual element that has had an onclick handler set by this function.
      5. additionally, when the user presses a keyboard shortcut that was set earlier, such as 'alt-a', the element that the keyboard shortcut corresponds to will be triggered by a simulated 'onclick' event.

### Rails

* I want to know how many things are in a collection and I don't want to remember how 3 different methods work.
  * Use [#size](https://stackoverflow.com/questions/6083219/activerecord-size-vs-count)
