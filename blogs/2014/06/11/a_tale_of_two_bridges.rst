A tale of two bridges
=====================

I was looking forward to opening the email and seeing the drawings.

They were line drawings, comic style.  Here is the first drawing:

.. image:: https://raw.githubusercontent.com/johnnygill/jackanory/master/art/leona/bridge1.png
   :height: 410 px
   :width:  562 px

You can see Dave's sweater slowly unravelling and being used to hold
the whole shakey structure together.

The deck of the bridge represents the software platform, or rather,
platforms, as each section of the bridge seems to have a different
design.

The monitor is displaying an error message, which bleeds into the
ravine (the ANY key is a tongue-in-cheek reference, which is placed
high in the sky so as to be an unattainable solution);

The *city* represents frustrated, dismayed and angry users, on the
edge of the ravine, all they want is a simple bridge to lead them
across. 

Why software invariably ends up looking like this bridge
--------------------------------------------------------

Building great software is hard.  Ironically, building mediocre
software is probably harder.  As with the bridge builders things are
often made difficult for the engineers.  They have many arbitary and
unhelpful constraints from their own management, most of whom have
forgotten why these rules were introduced in the first place and none
of whom have ever used the tools that the engineers are using.

They are invariably dealing with many different systems, built with
different technologies.  Often these are proprietary systems which come
without the actual source code.  So, if a system does not quite work
as it is supposed to they just have to work around it.  

If they are lucky the system comes with support and there is someone
at the end of a phone line who has never actually written any code,
but who has a script to follow.  And if you stick with them for the
next 2.5 hours might get you to the point where they say, "Well we
haven't seen that error before".   

They file a bug and for the next two releases you eagerly install the
new version only to find your bug hasn't been fixed.

By the third release you have found a cunning way to actually take
advantage of the bug to do some neat stuff you couldn't do if the code
actually worked as intended.  So you build a whole new analysis system
around that bug, only to discover they fixed it in the fourth release.

Every member of the team is an expert on one system or another, one
language or another.   It has taken them years to get to this level of
comfort with their tool of choice.  They remember the pain of getting
there, they fear the day they have to switch to something new, go
through all that pain again.  They strongly believe that the tools
they use are the very best (after the pain they have gone through to
master it all, they had better be). 


So is there a way to build software teams that actually works?
--------------------------------------------------------------

It turns out, there is.  People have been doing it for decades now.
It is called *open source*.  Although, I think I prefer *open
literature*.

But first, the tale continues. 

The residents of the city were angry, but things got worse when the
company they had paid to build the bridge went bust.  Something to do
with a lawsuit due to one of their previous projects and some people
that died using it.

Someone called Richard had a workshop in which he built tools.  Many
people in the city thought he was a little crazy.  He had a huge beard
and didn't get out much.   But he built great tools.  He also wrote
instruction manuals telling you how to build those tools.

He would gladly give you the tools he built, but insisted on giving
you a copy of his instruction manual too.  He was delighted if you
used it to build more tools and was also happy if you sold them or
gave them to others.  But he insisted that you also give them a copy
of the instruction manual.

He loved it when you found new ways to build tools and updated your
copy of the instruction manual.  But, he insisted that if you gave
anyone one of the tools you had built that you give them the full
instruction manual telling them how to build the tool.  So they could
build new tools, just like Richard let you do.

Well along came Linus.  He used to build wooden components.  He used
Richard's tools and like Richard, gave away his components, along with
the instruction manuals he had used to make them.

Beowulf came along and used Linus's manual to teach himself how to
link together these wooden components and make some really beautiful
structures. 

Larry started building tools that helped you do wonderful things with
string.  Larry's tools let you take strings and weave them into ropes
and baskets, nets and a whole wonderous world of things.

But, strings are delicate things and after a while threads would start
to come unravelled.  People who built stuff with Larry's string tools
also passed on their instruction manuals, but these manuals were
really hard to read.  Even the person who wrote them would struggle to
follow the manual a year or so after it was written.

By now there were little cottage industries everywhere, writing tools
to work with string.  Guido came along and read the instruction books
for all these tools and used these books to help him build his own
string building tool.

His manual was easy to read and when you used it to build new tools to
do things with strings the manuals for those tools were really easy to
follow.  Guido also introduced a thing he called the *GIL*.  Nobody
really understood this thing, but Guido insisted it was really
important and would help stop threads unravelling.

Well by now, many of the people of the city were working with all
these tools and doing some wonderful things.  

Managing all these instruction manuals was becoming a bit of a
challenge.  There were thousands of manuals and each manual came in
lots of versions.  

Libraries sprung up to hold the manuals.  The libraries all had
strange names like *sccs*, *rcs*, *cvs* and *svn*.  The neat thing was
the libraries came with instruction manuals that helped you use them.

Linus grew frustrated with these libraries, as did others and they
came up with a new type of library that made it easy for anyone to
take a copy of the whole library and create a new library.

Linus created a library called *git*.  Others created *bazaar* and
*mercurial*.  Life was good.

But, few people could understand how *git* worked.  Some read the
manual Linus had written and managed to figure it all out.  They made
changes to the manual, made it easier to read and created new types of
*git* library that mere mortals could also use.  And they taught each
other how to use the library.

Well by now the people of the city were hard at work on the bridge.
And bit by bit, using all these tools, they transformed it into this
beautiful, simple structure:


.. image:: https://raw.githubusercontent.com/johnnygill/jackanory/master/art/leona/bridge2.png
   :height: 562 px
   :width:  410 px

Jacob came along on his pony and rode across the bridge to the
beautiful oasis on the other side.


.. author:: default
.. categories:: none
.. tags:: none
.. comments::
