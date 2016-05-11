---
layout: page
title: Resources for Programmers
tagline:
sidebar_title: Resources
in_sidebar?: true
---

## Borrowing Testing Devices
* [Reservations](https://reservations.yale.edu/sdmp)

## APIs
* [Codecademy APIs course](http://www.codecademy.com/tracks/apis)
* [Yale API Portal](https://developers.yale.edu/)

## Command line / Terminal
* [Learn the Command Line the Hard Way](http://cli.learncodethehardway.org/book/) -
 a somewhat long, but complete (exercise-heavy) guide to using the command line.
 If you're not already comfortable with the command line, you should do this.
 If you're comfortable with the command line, you should still probably do this.
* Customizing
  * OS X's Terminal application has a lot of configurable settings under
  Preferences.
  * [Dotfiles](https://github.com/YaleSTC/wiki/wiki/Dotfiles) can help make your
  command prompt beautiful.

## Databases
* [Learn SQL The Hard Way](http://sql.learncodethehardway.org/book/)
* [Postgres, the Best Tool You're Already Using](http://adamsanderson.github.io/railsconf_2013/?full#1)
* [Visual Explanation of SQL Joins](http://www.codinghorror.com/blog/2007/10/a-visual-explanation-of-sql-joins.html)

### Supplementary
* [Use the Index, Luke! (SQL Tuning and Indexing)](http://use-the-index-luke.com) -
This is an in-depth guide to how indexes work in SQL DBs, more of an advanced topic, but
it's really interesting.

## Git
* [Try Git](http://www.codeschool.com/courses/try-git) - A great interactive
intro to git. Start here.
* [Git Immersion](http://gitimmersion.com/) - A great next step to take what you
learned in 'Try Git' and apply it to your own computer.
* [Pro Git](http://git-scm.com/book) - *the* reference book for git.
* [Git from the Bottom Up](http://ftp.newartisans.com/pub/git.from.bottom.up.pdf) (pdf)
* [Git branching model](http://nvie.com/posts/a-successful-git-branching-model/)
* [Git Visual Cheatsheet](http://ndpsoftware.com/git-cheatsheet.html) -
great for reference while you're coding ("what's that command again?")

### Create and sync a local branch with Github
*The following commands create both a remote and local branch with tracking
between them and check out the local branch. Make sure your base branch is
up-to-date!*

```
git push origin [BASE_BRANCH]:refs/heads/[NEW_BRANCH_NAME]
git fetch origin
git branch --track [NEW_BRANCH_NAME] origin/[NEW_BRANCH_NAME]
git checkout [NEW_BRANCH_NAME]
```

For example:
```
git push origin development:refs/heads/404_branch_not_found
git fetch origin
git branch --track 404_branch_not_found origin/404_branch_not_found
git checkout 404_branch_not_found
```

## HTML & CSS
* [A Practical Guide to HTML & CSS](http://learn.shayhowe.com) - A fantastic and
relatively complete introduction to HTML & CSS
* [W3Schools HTML Tutorials](http://www.w3schools.com/html/default.asp) and
[CSS Tutorials](http://www.w3schools.com/css/default.asp) - The canonical and
definitive resource for HTML/CSS. Not the clearest source, but still valuable.
* [A Detailed HTML Overview](http://ithare.com/a-detailed-html-overview/) - An in-depth
overview of HTML.

### Supplementary
* [How Browsers Work](http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)
* [CSS Layout Overview - LearnLayout.com](http://learnlayout.com/)
* [CSS Positioning 101](http://alistapart.com/article/css-positioning-101)
* [CSS Floats 101](http://alistapart.com/article/css-floats-101)
* [CSS Overflow](http://css-tricks.com/the-css-overflow-property/)
* [CSS Floats](http://css-tricks.com/all-about-floats/)
* [Learn CSS Positioning in Ten Steps: position static relative absolute float](http://www.barelyfitz.com/screencast/html-training/css/positioning/) - a bit outdated, but still interesting
* [Centering in CSS](http://www.w3.org/Style/Examples/007/center.en.html)
* [Span vs Div & Inline vs Block](http://dustwell.com/div-span-inline-block.html)
* [Child Selectors](http://www.w3.org/TR/CSS2/selector.html#child-selectors) vs [Descendant Selectors](http://www.w3.org/TR/CSS2/selector.html#descendant-selectors)
* [TutsPlus 30 CSS Selectors You Must Memorize](http://code.tutsplus.com/tutorials/the-30-css-selectors-you-must-memorize--net-16048)

## JavaScript

### Books
* [JS the good parts](http://www.amazon.com/dp/0596517742/?tag=stackoverfl08-20)
* [Eloquent JavaScript - Intro to JS](http://eloquentjavascript.net/contents.html)

### Interactive
* [CodeSchool](http://www.codecademy.com/tracks/javascript)
* [Codecademy](http://www.codecademy.com/tracks/javascript)

### Reference
* [Mozilla Reference - Lots of good links](https://developer.mozilla.org/en/docs/JavaScript)
* [Reintroduction to JS](https://developer.mozilla.org/en-US/docs/JavaScript/A_re-introduction_to_JavaScript?redirectlocale=en-US&redirectslug=A_re-introduction_to_JavaScript)
* [Superhero JS - Advanced JS Articles](http://superherojs.com)

### Videos
* [Crockford on JS - Video Lecture Series](http://yuiblog.com/crockford/)

## Rails
* [Model View Controller (Lynda)](http://www.youtube.com/watch?v=3mQjtk2YDkM)
* [Agile Web Development with Rails, 4th Ed](http://www.amazon.com/Agile-Web-Development-Rails-Programmers/dp/097669400X)
  * available in the Developers Program Library
* [RailsCasts](http://railscasts.com)
* [Getting Started with Rails](http://guides.rubyonrails.org/getting_started.html)
* [Rails for Zombies](http://www.codeschool.com/courses/rails-for-zombies-redux) (also see part 2)

### Directory structure
* [Rails Anatomy](https://www.codeschool.com/code_tv/rails-anatomy)
* [What code goes in the lib/ directory?](http://blog.codeclimate.com/blog/2012/02/07/what-code-goes-in-the-lib-directory/)

### Debugging
* [A Comprehensive Guide to Debugging Rails](http://www.jackkinsella.ie/2014/06/06/a-comprehensive-guide-to-debugging-rails.html)

### Testing
* [Learn TDD Without Getting Overwhelmed](http://www.justinweiss.com/blog/2014/06/02/how-to-learn-tdd-without-getting-overwhelmed/)
* [Team Treehouse's Intro to RSpec](http://blog.teamtreehouse.com/an-introduction-to-rspec)
* [The RSpec Book](pragprog.com/book/achbd/the-rspec-book‎)
  * available in the Developers Program Library
* [TutsPlus RSpec](http://code.tutsplus.com/tutorials/ruby-for-newbies-testing-with-rspec--net-21297)
* [TestFirst](testfirst.org/learn_ruby)

### Advanced
* [Sync - Realtime Rails Partials - chrismccord](http://chrismccord.com/blog/2013/04/21/sync-realtime-rails-partials/)
* [DevMynd - Effective Rails - Part 2 - Hiding ActiveRecord](http://www.devmynd.com/blog/2013-3-effective-rails-part-2-hiding-activerecord?utm_source=rubyweekly&utm_medium=email)

## Ruby

### Core Content
* [Learn to Program (Chris Pine)](http://pine.fm/LearnToProgram/) -
Great into to programming in general, that uses the Ruby Language. Suitable for beginners, intermediates may get something out of it as well. It's very thorough and clear, building from the bottom up.
  * available in the Developers Program Library.
* [Why's Poignant Guide](http://mislav.uniqpath.com/poignant-guide/book/) -
Quirky Intro to Ruby (Comic?)
  * Some ruby has changed, like hash notation
* [Matz' Ruby User's Guide](http://www.rubyist.net/~slagell/ruby/) - lots of
examples to illustrate points, good table of contents
* [Humble Little Ruby Book](http://www.humblelittlerubybook.com/)

### Interactive, Hands-On
* [Try Ruby](tryruby.com) - a quick whirlwind introduction to things that exist
in Ruby. Hard to learn Ruby from this but it's good to quickly see what Ruby exists.
* [Ruby Monk](http://www.rubymonk.com/) - a full intro to ruby book with
interactive examples. Not as good of a starting point as Chris Pine's
LearnToProgram, but a wonderful second resource.
* [Ruby Koans](http://rubykoans.com) - a thorough test-driven walkthrough of
most of Ruby's features. You'd learn soo much about Ruby after doing this, but
it's only useful after having programmed using Ruby already.

### For Purchase
* [Programming Ruby (The Pickaxe Book)](http://pragprog.com/book/ruby4/programming-ruby-1-9-2-0)
  * available in the Developers Program Library
* [Eloquent Ruby](http://www.amazon.com/Eloquent-Ruby-Addison-Wesley-Professional-Series/dp/0321584104)
* [CodeAcademy - Ruby](http://www.codecademy.com/tracks/ruby)

### Iterators
* [Loops & Iterators](http://www.skorks.com/2009/09/a-wealth-of-ruby-loops-and-iterators/)
* [Select, Reject, Collect, Inject, Detect](http://matthewcarriere.com/2008/06/23/using-select-reject-collect-inject-and-detect/)

### Exceptions & Error Handling
* [Ruby Exceptions - RubyLearning](http://rubylearning.com/satishtalim/ruby_exceptions.html)
* [Ruby Exceptions - Bastard's Book](http://ruby.bastardsbook.com/chapters/exception-handling/)

### Cheat Sheets
* [ZenSpider's Cheat Sheet](http://www.zenspider.com/Languages/Ruby/QuickRef.html)
* [Learn Ruby in Y Minutes](http://learnxinyminutes.com/docs/ruby/)

### Refactoring
* [SourceMaking's Refactoring Guide](http://sourcemaking.com/refactoring/)

### Other
* [Understanding Ruby Symbols](http://glu.ttono.us/articles/2005/08/19/understanding-ruby-symbols)

## Sinatra
* [Sinatra Restafari Book](http://sinatra.restafari.org/book.html)
* [Rails Sinatra Comparison PDF](http://www.christopher-wood.com/papers/RailsSinatraComparison.pdf)

## Web app basics (Ruby)
* [How The Web Works Overview](http://mkcohen.com/how-the-web-works-in-one-easy-lesson)
* [What are HTTP Requests](http://www.jmarshall.com/easy/http/#whatis)
* [A Beginner's Guide to HTTP and REST](http://code.tutsplus.com/tutorials/a-beginners-guide-to-http-and-rest--net-16340)
* [How HTTP Requests relates to Rails](http://dablog.rubypal.com/2008/11/24/restful-rails-for-the-restless)
* [Quick Introduction To Rack](http://rubylearning.com/blog/a-quick-introduction-to-rack/)
* [Very basic rack application example](https://gist.github.com/mattetti/1447058)

### Routes
* [Wikibooks - Short Rundown](http://en.wikibooks.org/wiki/Ruby_on_Rails/Routing#RESTful_routes)
* [Restful Rails (advanced)](http://b-simple.de/download/restful_rails_en.pdf)

### ERB
* [Stuart Ellis' Guide to .erb](http://www.stuartellis.eu/articles/erb/)

## Miscellaneous

### Documentation
* [Writing great documentation](http://jacobian.org/writing/great-documentation/)

### Optimization
* [Evan Travers : Workflow in Tmux](https://coderwall.com/p/_g2vpq)

### Pair Programming
* [Thoughts on programming](http://articles.coreyhaines.com/posts/thoughts-on-pair-programming/)
* [Pair learning for educators](http://realsearchgroup.org/pairlearning/educators.php)
* [The power of pair-programming in collaborative learning](https://www.ncwit.org/resources/pair-programming-box-power-collaborative-learning)
* [Subliminal Collaborator: SublimeText v2 remote pair-programming plugin](https://github.com/nlloyd/SubliminalCollaborator)

### Regular Expressions
- [An interactive RegEx Tutorial](http://regexone.com/)
- [The canonical RegEx reference](http://www.regular-expressions.info)
- Regular expression testers make writing regexes wayyy faster.
  - Ruby: [Rubular](http://rubular.com)
  - JavaScript: [RegexPal](http://regexpal.com/)
- [Thoughtbot Regular Expressions](http://robots.thoughtbot.com/back-to-basics-regular-expressions)

### Screencasts
* [Destroy All Software Screencasts](https://www.destroyallsoftware.com/screencasts)

### UI
* [The method still works - (37signals) UI Design](http://www.37signals.com/svn/posts/1681-the-method-still-works)
User Interface / User Design / User Experience / Human Computer Interaction
* [HCI Class](http://hci-class.org) - excellent online course. It's definitely
worth watching the first couple (3?) of weeks' lectures at least. (You can watch
 lectures if you click "preview course" even if you don't sign up \[although
 it's free and riskless to sign up and keep track of your progress\].)
* [UX Crash Course](http://thehipperelement.com/post/75476711614/ux-crash-course-31-fundamentals) -
a good online resource which goes through design fundamentals

### Other
* [How to be a program manager - Joel on Software](http://www.joelonsoftware.com/items/2009/03/09.html)
* [Cheat Sheets](http://devcheatsheet.com/)
