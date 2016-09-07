Code Reviews
=======

author
: Colin Dean -> @colindean

subtitle
: Last Bastion of Brutal Honesty

theme
: nari

allotted-time
: 300

Introduction
============

![Colin Dean - @colindean](http://i.imgur.com/OQjWfCX.jpg){:relative_height='35' align='left' reflect_ratio='0.1' }

* Software Engineer @ IBM (formerly Vivísimo)
* President @ Meta Mesh
* Advisor @ Code & Supply
* Advisor @ Imagine Careers

Obligatory statement
====================

> All opinions are my own and not that of my employer(s).

Credentials
===========

* Lone wolf developer on international team 2008-2009
* Professional services consultant 2009-2014
* Software engineer on highly functional team 2014-
  * Tech Lead since late 2014

Experience life at a high rate of WTFs per minute
=================================================

Code Reviews
============

Main points
===========

* Code Review is your chance to
  * critique the code
  * own the code by proxy
  * make the code as if you had written it
  * make the code into something you could maintain

Honest & focused without ego in the way
=======================================

Enables *continuous* evolution of style and methods

Explanation and Response
========================

critique | learning

Code Reviewers are lawyers we want
==================================

Screening and minimizing risk

If Code == Debt
===============

* Team *analyzes* debt
* Team *minimizes* debt
* Team *accepts* debt†

† including small print

Immediate fix vs backlog
============================

Team as credit raters
=====================

    // XXX   risky business, fix ASAP
    // FIXME safe for now, revisit soon
    // TODO  low risk + enhancements

Group effort, group acceptance
==============================

Commit or patchset = my/their code

Master = our code

Healthy conflict
================

Conflict is OK
==============

as long as it's not personal

Talk about code not people
==========================

"This design doesn't allow..."

vs

"You didn't consider"

"The code" not "You"
====================

Pick battles
============

* Make progress
* Don't be pedantic
* Accept debt
* Identify high churn lines

Things we look for
==================

* Complexity of algorithms and loops
* Exception handling
* Exception naming
* Logging sufficiency

Things we look for
==================

* Style conformation
* Variable naming
* Long lines
* Long methods

Things we look for
==================

* Readability
* Extraneous/Unnecessary Comments
* SLOC 𝛥
* Single Purpose
  * ("and" as a red flag)

But really,
===========

* Does it work?
* Is it tested?

Productive Commenting
=====================

* Attack - "wtf is this crap."
* Statement - "I don't like this."
* Pickyness/pedantry - "Whitespace!"
* Constructive Criticism - "This would perform better if..."

Sometimes meatspace is better
=============================

Learn when to *talk*, not post more

Useful images
=============

![WTFs per minute](http://blog.codinghorror.com/content/images/uploads/2009/02/6a0120a85dcdae970b012877707a45970c-pi.png)

References
==========

* [Code Reviews: Just Do It](http://blog.codinghorror.com/code-reviews-just-do-it/) by Jeff Atwood
* [Peer Reviews in Software: A Practical Guide](http://www.amazon.com/exec/obidos/ASIN/0201734850/colingrad-20) by Karl Wiegers
* [How to write the perfect pull request](https://github.com/blog/1943-how-to-write-the-perfect-pull-request) by Keavy McMinn
* [How a junior feels during a code review](http://devopsreactions.tumblr.com/post/88653874397/how-a-junior-feels-during-a-code-review) - DevOps Reactions
