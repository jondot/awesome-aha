# Awesome "Aha!"

Some times you don't know where to start. Sometimes you just dont "get" it.
We're flooded with information and resources, but we, the more experienced lot,
all know which ones really made it sink for us.

This is a list of the best starting points that helped experienced
people learn new things quickly, and those pivotal resources that made an "Aha!" moment.


**NOTE: as such, this list is very carefully groomed, not all suggestions will be accepted,
but we'll do our best**


_Guidelines for submitting a topic:_

* It should be critically acclaimed.
* Prefer the original, timeless, resource over a derivative of it (such as a blog post).
* Prefer a derivative (such as an article, blog post, book) of the original when it really
is known to explain the subject in a better way.
* Any form of a resources is good: Books, videos, courses, talks, and more.
* When in doubt, just submit a PR and we'll help find the best way to make it into the list.

_Legend_:

* :pushpin: - timeless
* :book: - book
* :coffee: - accessible, coffee time reading
* :mortar_board: - academic / heavy reading
* :pineapple: - fresh, recent development
* :wrench: - makes you a pragmatic programmer



Many thanks to everyone on the contributor list :)

## Technology

_How to judge technology and develop a good gut feeling_

* :pushpin: :coffee: [Five things we need to know about technological change](http://web.cs.ucdavis.edu/~rogaway/classes/188/materials/postman.pdf) - a classic, mind opening essay about technology and people.
* :coffee: [Beating the Averages](http://paulgraham.com/avg.html) - how programming languages are related to a mindset.


## Operating Systems

_Understanding the almost-mechanical pieces on top of which we run our software_

- :pushpin: [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/) - probably the most accessible book about operating systems. Don't have to read this cover to cover, just hunt out interesting bits you like.


## Unix

_It's an operating system, but also a mindset and a cult_

* :pushpin: [The Cathedral and the Bazaar](http://www.catb.org/esr/writings/cathedral-bazaar/) - "get" open source.




## General Programming

_Pure programming, problem solving, detached of specific technology_

* :book: :pushpin: [Programming Pearls](https://www.amazon.com/Programming-Pearls-2nd-Jon-Bentley/dp/0201657880) - programming and problem solving.
* :book: :pushpin: :mortar_board: [SICP](https://mitpress.mit.edu/sicp/) - Structure and Interpretation of
  Computer Programs. For some, hard read. However, pivotal for understanding
  abstraction and Scheme makes the perfect beginner FP language. If you have
  time, invest it. Otherwise, try finding gists of the ideas in this book such
  as [here](www.sicpdistilled.com).
* :book: :wrench: :pushpin: [The Pragmatic Programmer](https://www.amazon.com/Pragmatic-Programmer-Journeyman-Master/dp/020161622X) - a classic on a pragmatic thinking for programmers. Was a pivotal part
of driving a new era of thinking, tools, languages and platforms.
* :coffee: [better errors](http://elm-lang.org/blog/compiler-errors-for-humans) opens your mind to the idea of giving humans better compiler errors (as implemented in Elm, written by Elm's creator).
* :mortar_board: [The LISP Paper](https://www.brinckerhoff.org/clements/csc530-sp09/Readings/mccarthy-1960.pdf) _1960_, this is where John McCarthy introduces [LISP](https://en.wikipedia.org/wiki/Lisp_(programming_language)), and introduces the world to: recursion, naming
variable with more than a single letter (as was done because of math), and if/else expressions. Later, non-functional languages would adopt it. Thanks, John!.
* :coffee: [Greg Young on Software](https://vimeo.com/108441214) - (video) a few observations about what makes a good or bad codebase, a good or bad design. Spoiler: it's the code size; sort of. Has many
other good observation if you have not a lot of experience. Very repetitive, but good.
* :coffee: :pushpin: [Rob Pike's Notes on Programming in C](https://docs.google.com/document/d/1ZhB5a7MoY1hEkKcbn9TAB4bMSjyZZWer_6Q-EHKJeOc/edit?usp=sharing) - Really this could have been
called "shit people knew in 89' that people today will keep rediscovering and fight about - but will never stop to realize they're really reinventing a flatter wheel".
* :coffee: [Design Stamina Hypothesis (Fowler)](https://www.martinfowler.com/bliki/DesignStaminaHypothesis.html) - The emerging pop computing trend challenges good design because people keep adopting buzzwords and slapping stack overflow code snippets onto production. This
essay reminds us why good design is important and why it's so hard to justify good design or architecture in general.
* :coffee: [ID Software's 90's Programming Guidelines](https://www.youtube.com/watch?v=E2MIpi8pIvY) - (video) Amazingly relevant still, even today.


## Functional Programming

_Functional, and functional-style programming_

* :book: :pineapple: [Mostly Adequate Guide (to functional programming)](https://drboolean.gitbooks.io/mostly-adequate-guide) - a great tutorial if you want to short-circuit years of wax-on wax-off to properly
"get" FP. Start with this if you don't have FP background, or have some university clue, and progress to more heavy hitters such as Haskell, Lisp and so on.
* :coffee: :pineapple: [FP Jargon](https://github.com/hemanth/functional-programming-jargon) and [The Perfect API](https://james-forbes.com/?/posts/the-perfect-api) - pair the "Mostly Adequate Guide" with these, either while reading, or after finishing reading it, to bolt in 
place all of the FP magic. These will also serve as a good cheatsheet for later.
* :coffee: [Some History of Functional Programming Languages](https://www.cs.kent.ac.uk/people/staff/dat/tfp12/tfp12.pdf) - Turner summarizes part of the history of FP languages. Good to skim and to get a feeling of the evolution.
* :pushpin: [Introduction to Functional Programming](https://www.amazon.com/Introduction-Functional-Programming-Prentice-Hall-Paperback/dp/B00OVNLJTS) - Wadler and Bird's classic. Many FP concepts first introduced here. Search on Google for more usable copies.
* :pushpin: [What's a Transducer](http://raganwald.com/2017/04/30/transducers.html) - A modern take on explaining transducers with Javascript (ES6), but read it any way because it intros map, filter, reduce and so on.



## Patterns

_Design patterns in depth_

* :pushpin: :mortar_board: [MVC](http://heim.ifi.uio.no/~trygver/1979/mvc-1/1979-05-MVC.pdf), [MVP](http://www.wildcrest.com/Potel/Portfolio/mvp.pdf) - the original articles. MV-[wildcard] patterns will keep popping up,
but you must understand their original context, and see that it was so different than what they are used for today.




## Data

_How to treat data, and datastructures_

- :pineapple: :coffee: [Log structured merge trees](http://www.benstopford.com/2015/02/14/log-structured-merge-trees/) - the data structure that powers
a lot of recent big data products.


# Ops

_Servers, ops, and compute centers_

- [My (Rob's) Philosophy on Alerting](https://docs.google.com/document/d/199PqyG3UsyXlwieHaqbGiWVa8eMWi8zzAn0YfcApr8Q/edit) - The orignal raw document that kickstarted [this case study](https://www.oreilly.com/ideas/monitoring-distributed-systems) by Rob Ewaschuck. I prefer
the raw original because it passes a sense of "There's no silver bullet" so I treat it as a discusion or knowledge sharing. Don't take
it as the prescriptive way to go (and, of course, do read the [Google SRE book](https://landing.google.com/sre/book.html), etc.)




## Programming Languages

_High precision pointers into various programming languages_

### Go

- [Golang Notes](https://github.com/luciotato/golang-notes) - coverage of several subjects from a programmer's perspective, including a bit of internals.




## Effectiveness

_Be a more effective engineer_

- :coffee: [How to read a book in a week](https://hbr.org/2016/02/how-to-read-a-book-a-week) - this is good for some nonfiction books, but all academic papers.
- :coffee: [How to read an academic paper](http://blizzard.cs.uwaterloo.ca/keshav/home/Papers/data/07/paper-reading.pdf) - changed the way I read papers and made me immediately more effective. Wish I had that when I was in university.


## Frameworks

_High precision pointers into various frameworks_

### React

- :coffee: :pineapple: [React implementation
  notes](https://facebook.github.io/react/contributing/implementation-notes.html)
  and the [guiding
  principles](https://facebook.github.io/react/contributing/design-principles.html). They are simple to understand and
  well crafted. Read these even if you don't know what React is. If you're
  still not convinced, read [their implementation
  principles](https://facebook.github.io/react/contributing/design-principles.html#implementation), it felt like my 20 years of experience trying to build perfect APIs distilled into a small number of simple ideas.



## Mechanics

_Focusing on tools and practices_

### Programming Languages

- :wrench:  [Learn X in Y Minutes](https://learnxinyminutes.com) - a highly
  effective website for polyglots, for refreshers, and the gist of many
  programming languages. Use this if you're already experienced with
  programming.


### Vim

- :pushpin: :coffee: [Seven habits of effective text editing](http://www.moolenaar.net/habits.html)
- :wrench: [Vim Bootstrap](http://www.vim-bootstrap.com/) - a great `vimrc` generator with sane defaults.
- :coffee: [A Good Vimrc](https://dougblack.io/words/a-good-vimrc.html) - a soft and reasonable introduction to vim configuration that makes sense.





## You

_About your own self, mental modes, and more_

### Habits and Learning

- :coffee: [Summary of Super Human by Habit](https://sivers.org/book/SuperhumanByHabit) by Derek Sivers. Most of the points listed are great and some are so-so; you can get the gist of the ideas without reading the book.


## Next Steps

_Where to go from here?_

You might want to discover things on your own. When you're done with this list, I'd recommend spending some time with these.

- [papers we love](https://github.com/papers-we-love/papers-we-love) - an amazing compilation of academic papers on many subject. Remember, there _are_ probably papers that are missing from this repo out of copyright reasons.
- [Microsoft research portal](http://academic.research.microsoft.com/) - Microsoft grabbed a lot of pioneers in computer science, there's plenty of great content there.
- [Google research](http://research.google.com/pubs/papers.html) - same for Google.

