# tidybib

A dirty hack to combine multiple BibTeX files into one, with a few formatting
and tidying conventions added in.

## Introduction

This small python program was born when I began to write my doctoral
dissertation at the University of Nebraska. Because I wished (for some sick
reason) to write my dissertation in LaTeX, I needed to convert my EndNote
(gag!) reference libraries into BibTeX, which was easily done. I then had
to combine them into a single BibTeX file, organize them by journal name,
sort them by publication date within each journal, and strip out all the crap
that EndNote drops into its BibTeX files.

So, tidybib fills that need. Long story short, I'm anal about BibTeX and LaTeX
source file formatting and I wrote a quick hack to satisfy my need for
consistency and structure. It's sad, really.

## Notice

No guarantees that this will work for you, but it should barf pretty hard if
you try and feed it files that aren't formatted as it expects. One thing to
make sure of is that no email addresses (i.e. no ampersands) are present in
the BibTeX fields, and that each field only occupies a single line of text
in the input files.

