---
layout: index
---
### Welcome to the Markdown Community Page
[Markdown][1] is

> a text-to-HTML conversion tool for web writers. Markdown allows you to
> write using an easy-to-read, easy-to-write plain text format, then
> convert it to structurally valid XHTML (or HTML).

This page is maintained by and for the markdown community to document various
tools and resources available to document authors and developers, as well as
implementors of the various markdown implementations.

### Authors
Coming soon...

### Developers

Whether you're building a web site, a text editor, or something else, if your
project needs to process markdown documents, you'll need to chose an 
[implementation][2] of a parser library. While the language your project is 
coded in will likely have the largest impact on which implementation you
chose, there are a number of other factors to consider. Is performance 
a high priority? Perhaps bindings to a C library will suit you best.
Will untrusted users be able to post documents to your wed site? Be sure
you are sanitizing the HTML to avoid XSS attacks and the like. Do you
want to offer support for a superset of Markdown's syntax? Will you
be writting your own superset? Some implementations come as/is, while
others have varying degrees of customability. Will your project have an
international audience? Perhaps an implementation that supports Unicode
input and/or right-to-left text is right for you.

### Implementors

If you would like to develop your own implementation of the parser, you may
want to take a look at the rather lengthy list of existing [implementations][2]
already out there (if your implementation is missing from the list, please add it).
Obviously, not every one of those implementations parses markdown text in exactly 
the same way. As this fragmentation of Markdown can cause frustration to the
document author, it is important to be aware of the existing implementations
and how they behave. The very useful tool, [Babelmark 2][3], has been provided
by John MacFarlane to compare the output of various implementations. See John's
[FAQ][4] to add your implementation. The FAQ also discusses why this all matters
and provides examples of some common edge cases that various implementations 
disagree on.



[1]: http://daringfireball.net/projects/markdown/
[2]: https://github.com/markdown/markdown.github.com/wiki/Implementations
[3]: http://johnmacfarlane.net/babelmark2/
[4]: http://johnmacfarlane.net/babelmark2/faq.html#how-can-i-add-my-markdown-implementation-to-babelmark-2
