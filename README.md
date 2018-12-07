# davidlowryduda.com

This repository contains the contents and notes for davidlowryduda.com. It's
sort of astounding that I haven't created a repo for this before. Older content
might slowly appear here. Or it might not.


Input Formats
-------------

The content that appears on davidlowryduda.com starts in one of three major
ways. It either starts as a Markdown+mathjax, or as a LaTeX file, or as a
jupyter .ipynb notebook. I have a small set of utilities that convert from any
one of these to html files that are hosted on davidlowryduda.com.

- Markdown+mathjax --> html through python-markdown2 (or pandoc if I don't use
    minor customizations)
- .tex --> html through latex2jax, a small script that I wrote
- ipynb --> html through nbconvert

There are a few custom tags that I process on davidlowryduda.com with
javascript. A particularly common one is [note]...[/note], which are ultimately
transformed into footnotes.


Note on Licensing
-----------------

Any code in this repository is licensed under the MIT license unless otherwise
specified. A copy of this license is included in the repository.

All prose, including the content of .tex files and .markdown files, is given
under the CC-BY-NC (3.0) Creative Commons license. A copy of this license is
included in the repository.

I expect that this will not matter. If for some reason it does and you require
more permissive licensing, then contact me.
