epub3sample ===========

Repository for experiments in conversion of LaTeX to epub3 using
[tex4ebook](https://github.com/michal-h21/tex4ebook)

Contents --------

- [hsmmt10t.epub
  ](https://github.com/michal-h21/epub3sample/raw/master/hsmmt10t.epub)

  David Eugene Smith: *History of Modern Mathematics*.  Source file come from
[Project Guttenberg](http://www.gutenberg.org/ebooks/8746).  `\author` and
`\title` were added in order to compile with `tex4ebook`. Also macros for cover
inclusion and semantical division of front matter areas were added.
  
  In this stage, emphasis is placed on correct document structure, default
`tex4ht` styling and formatting is used, together with
[scale.css](https://github.com/viljamis/Scale) for better typography.
Particular `epub3` features used
are footnotes and `mathml` math. 
  
**Compiling**
       
    tex4ebook -c hej -f epub3 hsmmt10t.tex

you need to have [helpers4ht](https://github.com/michal-h21/helpers4ht)
installed in order to compile the example
