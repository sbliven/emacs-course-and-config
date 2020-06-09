
# Table of Contents

1.  [An Emacs Course Configuration](#org781a302)
    1.  [Introduction](#org2124fc8)
    2.  [Planning of learning stages](#orgc2f43ed)
2.  [Feedback](#orgf058fb9)



<a id="org781a302"></a>

# An Emacs Course Configuration


<a id="org2124fc8"></a>

## Introduction

I had used Emacs for many years in its most simple way - just as a
programming editor, just using the minimal set of exotic
commands. But when I discovered around 2009 what Emacs really is -
one of the most flexible and well documented programming
environments that happens to be a very good editor as well, I was
blown away.

Org mode was a revelation - the dream of every scientist (physical
chemistry was my original profession). A notebook where you could
write easy marked up text, math, you could calculate, and as a
programmer you could use all your programming languages inside of
the documents and produce graphics inline - too good to be
true. And then it is one of the best task management systems as
well. I fell in love, learned lisp - enjoined its different feel from
the C and scripting languages I knew - something that reminded me of
the joy of playing with the HP Scientific Calculators many year ago.

For a long time I entertained the hope of passing on the
knowhow. But it's not so easy, since the thing which makes Emacs so
great and efficient - its staggering flexibility - also makes it
tough to teach. Most long time users end up with configurations that
fit them like a glove. But other users will be very opinionated in regards
to the packages and optimizations that are used. There's a good number
of excellent meta-distributions around, like SpaceMacs or Doom. They
may be great for many users. I myself always stayed with my hand-written
config that I constantly adapted to more modern styles (which prevented
me from ever declaring the dreaded *Dot Emacs Bankruptcy*)

I now decided to make a first test run with a course that is based on
basic configuration of Emacs. I will start with an initial configuration
that already has a number of nice packages that will wet the appetite.
But the idea is not that learners shall adpot these exact configurations.
But they should learn how the configuration works, and how they can adapt
it. So, they by themselves will be able to make an informed decision about
whether they want to adopt one of the meta distributions, change the
present one, or just develop their own.


<a id="orgc2f43ed"></a>

## Planning of learning stages

This is what I am planning to cover. Let's see whether I'll be able to
pull throgh&#x2026;

The sequence beyond step 1 is up to change&#x2026; I will teach a small
number of work colleagues in this first round. I'll adapt to the
feedback I will get. All of this will be hands-on with prepared
documents for the lessons. The configuration will grow with the
material covered in the lessons.

1.  Basic Emacs and Org mode
    -   this is a big first stage, but I think that Org mode must be introduced
        early, because it is one of the principal features that immediately
        offers big benefits for new users
    -   minimal emacs lisp knowledge, just enough to understand the config
        in a rudimentary way and lose the fear of parentheses
    -   basic editing
    -   file management (dired)
    -   org mode as a basic task manager (org agenda, basic org file features)
    -   easier user interface with helm, smex, ido
    -   emacs package management
    -   how to use the info and help systems
    -   emacs daemon
2.  Emacs for higher productivity, programming and system management
    -   Magit - is there a better Git interface then this?
    -   Tramp (a killer feaure for users working on remote hosts. Loved by
        system administrators and developers)
    -   Org capture
    -   gpg for encrypting files
    -   dired revisited
    -   command execution from Emacs
    -   a look at some of the programming modes
    -   lsp-mode (a modern IDE interface in Emacs)
    -   linting (Syntax checking with flycheck)
3.  Authoring LaTeX, HTML, and other documents with Org mode
    -   write scientific documents containing math, preview the math
    -   do inline calculations with Calc
    -   include graphics and screenshots
    -   simple first steps with Org Babel to execute code and
        create graphics
4.  Org Babel for real
5.  Integrating with your browser
    -   Use emacs to edit forms in browsers like Firefox or Chrome
        (through the daemon)
    -   org-protocol: transfer information from the browser to Emacs,
        e.g. mark some text in the browser and get it into emacs, or
        convert a web page to org mode and find it ready in your buffer!
6.  Emacs and email
    -   mu4e and mbsync to manage email
    -   integrate email with org mode task management, making
        efficient use of org capture and email links in workflows.
7.  Emacs for science
    -   helm-bitex
    -   org-ref
    -   org-babel
    -   org-noter and PDF management
    -   jupyter (maybe)


<a id="orgf058fb9"></a>

# Feedback

I am very happy about feedback from the community. Please use this
project's issue tracker.

