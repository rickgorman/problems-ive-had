# problems-ive-had
A collection of problems I've run into, some with solutions.

## Environment

### Terminal emulator

* I want to know what different terminal fonts looks like.
  * [app.programmingfonts.org](https://app.programmingfonts.org/#camingocode)

### Shell

* I want to run a command based on the exit code of the previous command.
  * [if then syntax](https://stackoverflow.com/a/26675771)

### CLI tools

* I want to see realtime performance metrics for my Apple Silicon laptop.
  * [asitop](https://github.com/tlkh/asitop)

### Package management

* I want a reproducible set of brew packages.
  * [brew bundle dump](https://tomlankhorst.nl/brew-bundle-restore-backup/)

### Git

* I want fzf to help me pick a branch to checkout.
  * see [dotfiles](https://github.com/rickgorman/dotfiles)

## Notifications

* I want to know when someone on my team needs a code review.
  * [github slack integration](https://github.com/integrations/slack#subscribing-and-unsubscribing)
  * `/github subscribe OrganzationName/RepoName pulls`

## Browser

* I want to use keyboard navigation whenever possible.
    Unfinished GPT prompt:
      
      0. build a function that will do the following:
      1. when a user hovers over an element with an onclick handler, the element will be visually highlighted in some way
      2. when the visual highlight is visible, if the user presses the '!' key on the keyboard, a menu will show up and ask if the user wants to set a hotkey to activate that element.
      3. if the user say yes, then the user will be prompted to press a key combination with the 'alt' modifier, such as 'alt-a' or 'alt-5'. the user will then be notified that this choice has been remembered, which it will be. the ux described here will then go away.
      4. additionally, when the user presses the alt key on its own, small hover texts will appear over each visual element that has had an onclick handler set by this function.
      5. additionally, when the user presses a keyboard shortcut that was set earlier, such as 'alt-a', the element that the keyboard shortcut corresponds to will be triggered by a simulated 'onclick' event.

* I want to programatially hide the cursor.
  * [Pointer Lock API](https://developer.mozilla.org/en-US/docs/Web/API/Pointer_Lock_API)

## Rails

* I want to know how many things are in a collection and I don't want to remember how 3 different methods work.
  * Use [#size](https://stackoverflow.com/questions/6083219/activerecord-size-vs-count)
* I want to quickly navigate through things on a page via a command palette.
  * [Ninja Keys](https://www.youtube.com/watch?v=9pHxFkQ0JhU)
* I want to know which code paths are used most frequently.
  * [Coverband](https://github.com/danmayer/coverband)
* I have different roles accessing a controller action and I want to scope access to resources accordingly.
  * [Pundit policy_scope](https://github.com/varvet/pundit#scopes)
* I want to prevent N+1's from happening
  * [enabled strict_loading](https://www.bigbinary.com/blog/rails-6-1-adds-strict_loading-to-warn-lazy-loading-associations)

## MacOS

* I want super-fast access to a set of files (for instance, to run a test suite's db from).
  * Use a [ramdisk](https://gist.github.com/htr3n/344f06ba2bb20b1056d7d5570fe7f596)

## Design

* I want a simple set of design rules to work with.
  * [Safe Rules](https://anthonyhobday.com/sideprojects/saferules/)

## Clothing

* I want boots that will stand the [test of time](https://www.youtube.com/watch?v=Qm4BeXgM8ZM).
  * [Redwings](https://www.redwingshoes.com/work/mens/?grid=true)

## Keto

* I want mac and cheese but I can't have carbs.
  * [Chicken gnocchi and cheese](https://www.youtube.com/watch?v=R_yMyR946Yk)
