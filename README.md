# testsite2
---
title: Using R Markdown for Class Assignments
date: December 2017
output:
  html_document:
    toc: true
    toc_float: true
    theme: flatly
---

# Overview

## Test  Changed

R Markdown is a low-overhead way of writing reports which includes R code and
the code's automatically-generated output.  It also lets you include
nicely-typeset math, hyperlinks, images, and some basic formatting.  The goal
of this document is to explain, with examples, how to use its most essential
features.  It is _not_ a comprehensive reference.  (See rather
http://rmarkdown.rstudio.com.)

This guide assumes that you know at least some R.

This guide was adapted from <http://www.stat.cmu.edu/~cshalizi/rmarkdown>.


# What is Markdown?

[**Markdown**](http://daringfireball.net/projects/markdown/basics) is a
low-overhead mark-up language invented by John Gruber.  There are now many
programs for translating documents written in Markdown into documents in HTML,
PDF or even Word format (among others).
[**R Markdown**](http://rmarkdown.rstudio.com) is an extension of Markdown to
incorporate running code, in R, and including its output in the document.  This
document look in turn at three aspects of R Markdown: how to include basic
formatting; how to include R code and its output; and how to include
mathematics.

# Rendering and Editing

To write R Markdown you can use any text editor, a program which lets you read
and write plain text files.  You will also need R, and the package `rmarkdown`
(and all the packages it depends on).  I highly recommend using [R Studio](http://www.rstudio.com) which comes with a built-in text editor, and has lots of tools for, working with R Markdown documents.

### Rendering in R Studio

Assuming you have the document you're working on open in the text editor,
click the button that says "knit".
