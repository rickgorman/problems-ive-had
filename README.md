# problems-ive-had
A collection of problems I've run into, some with solutions.

## Environment

### Terminal emulator

* I want to know what different terminal fonts looks like.
  * [app.programmingfonts.org](https://app.programmingfonts.org/#camingocode)

### Shell

* I want to run a command based on the exit code of the previous command.
  * [if then syntax](https://stackoverflow.com/a/26675771)
* I want my shell history available across multiple terminal sessions at the same time.
  * [histappend](https://web.archive.org/web/20090815205011/http://www.cuberick.com/2008/11/update-bash-history-in-realtime.html)

### CLI tools

* I want to see realtime performance metrics for my Apple Silicon laptop.
  * [asitop](https://github.com/tlkh/asitop)

### Package management

* I want a reproducible set of brew packages.
  * [brew bundle dump](https://tomlankhorst.nl/brew-bundle-restore-backup/)

### Git

* I want fzf to help me pick a branch to checkout.
  * see [dotfiles](https://github.com/rickgorman/dotfiles)
* I accidentally force-pushed into a branch that others are working on.
  * Force-push again [from the previous head pointer.](https://evilmartians.com/chronicles/git-push---force-and-how-to-deal-with-it)

## Notifications

* I want to know when someone on my team needs a code review.
  * [github slack integration](https://github.com/integrations/slack#subscribing-and-unsubscribing)
  * `/github subscribe OrganzationName/RepoName pulls`

## Browser

* I want to use keyboard navigation whenever possible.
    Unfinished LLM prompt:
      
      0. build a function that will do the following:
      1. when a user hovers over an element with an onclick handler, the element will be visually highlighted in some way
      2. when the visual highlight is visible, if the user presses the '!' key on the keyboard, a menu will show up and ask if the user wants to set a hotkey to activate that element.
      3. if the user say yes, then the user will be prompted to press a key combination with the 'alt' modifier, such as 'alt-a' or 'alt-5'. the user will then be notified that this choice has been remembered, which it will be. the ux described here will then go away.
      4. additionally, when the user presses the alt key on its own, small hover texts will appear over each visual element that has had an onclick handler set by this function.
      5. additionally, when the user presses a keyboard shortcut that was set earlier, such as 'alt-a', the element that the keyboard shortcut corresponds to will be triggered by a simulated 'onclick' event.

* I want to programatially hide the cursor.
  * [Pointer Lock API](https://developer.mozilla.org/en-US/docs/Web/API/Pointer_Lock_API)
* I want to edit any random webpage in-line.
  * [document.DesignMode = "on"](https://developer.mozilla.org/en-US/docs/Web/API/Document/designMode)
* I want to access the element I just inspected.
  * type [$0](https://www.reddit.com/r/webdev/comments/dwb0kb/you_can_access_an_element_that_has_been_inspected/) in the console

### Css

* I want to know how all the `flex justify-content` options work.
  * [cheat sheet](https://i.imgur.com/PhzeOKq.gif) and [original](https://www.reddit.com/r/webdev/comments/10ffo7a/css_flex_for_speed_learners/)
* I want a reference for css flex, grid, and selection.
  * [cheat sheet](https://github.com/eludadev/css-docs)
  * [flex box](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  * [grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
* I want a reference for some of the more obscure parts of flex.
  * [cheat sheet](https://i.redd.it/vd9dc7wfk9471.png) and [original](https://www.reddit.com/r/webdev/comments/nvzhi0/flexbox_css_cheat_sheet/)
* I want to use a frosted glass effect.
  * [reference](https://www.reddit.com/r/webdev/comments/u5m4ue/frosted_class_effect_in_css_one_of_my_favorites/)
## Rails

* I want to know how many things are in a collection and I don't want to remember how 3 different methods work.
  * Use [#size](https://stackoverflow.com/questions/6083219/activerecord-size-vs-count)
* I want to quickly navigate through things on a page via a command palette.
  * [Ninja Keys](https://www.youtube.com/watch?v=9pHxFkQ0JhU)
* I want to know which code paths are used most frequently.
  * [Coverband](https://github.com/danmayer/coverband)
* I have different roles accessing a controller action and I want to scope access to resources accordingly.
  * [Pundit policy_scope](https://github.com/varvet/pundit#scopes)
* I want to guard against N+1's
  * On a per-spec basis, use [prosopite](https://github.com/charkost/prosopite)
  * For the entire app, use [strict_loading!](https://github.com/rails/rails/pull/37400) - [blog article](https://www.bigbinary.com/blog/rails-6-1-adds-strict_loading-to-warn-lazy-loading-associations)
* I want to run a bunch of queries in the same action, some potentially more than once, but I don't want to run the same query twice.
  * [rails query cache](https://web.archive.org/web/20230602162131/https://www.mendelowski.com/docs/ruby/rails-query-cache/) does that by default

### RSpec
* I want to see the entire error message, no matter how long it is.
  * Adjust the [maximum message length](https://github.com/rspec/rspec-expectations/issues/991#issuecomment-571644505)
* I want a general set of testing guidelines.
  * [thoughtbot guide](https://thoughtbot.com/blog/how-we-test-rails-applications)
* I want a guide for testing ActiveJob.
  * [ChuckJHardy's gist](https://gist.github.com/ChuckJHardy/10f54fc567ba3bd4d6f1)
* I want to speed up a slow test suite
  * Start with Evil Martian's [TestProf](https://test-prof.evilmartians.io/)

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
