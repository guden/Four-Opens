============
Introduction
============


This book is for the lost souls to guide them through the intricacies,
challenges and joys of building, maintaining, supporting and participating in
well balanced and sustainable open source communities.

Open source has become a loaded term over the past few decades while many
people still associate it with free software. While the access to source code
is directly implied in the term, under various license options that this book
will not discuss, the focus is shifting towards how the software gets created
by communities that are formed by a group of individuals who need to be able
to work together in an open environment while they often employed by companies
that are competitors.

What is the key to success to make open collaboration successful? How can you
participate in a community and help make it thrive? What are the most
important principles to follow during your journey?

This book will give you answers to these questions by describing a set of
guiding principles called The Four Opens that was originally defined by the
OpenStack community and helped them as well as other projects to thrive in the
open source ecosystem.


History
-------

Before jumping in the middle of The Four Opens let’s have a short tour in
history to understand where the need and the ideas came from. Originally, they
came from a need to do things differently.

Free software started in the 80’s by defining four (initially three)
freedoms [#fourfreedoms]_ that any free software should grant its
users:

* Freedom 0: freedom to run the program as you wish, for any purpose
* Freedom 1: freedom to study how the program works, and change it so it does
  your computing as you wish
* Freedom 2: freedom to redistribute copies so you can help your neighbor
* Freedom 3: freedom to distribute copies of your modified versions to others

These freedoms made the participants free to improve the program, and release
their improvements to the public, so that the whole community benefits.  But
free software did not mandate anything about how the software was to be built
to actually encourage this collaboration across boundaries that would result
in benefiting the whole community.

When open source was defined in 1998, it focused on a specific angle (the one
that mattered the most to businesses), which is the availability and
re-usability of the code. That also said remarkably little about how the
software should be built, and nothing about who really controls it. As a result
by 2010 most open source projects were actually closed one way or another:
their core development may be done behind closed walls, or their governance may
be locked down to ensure control by its main sponsor. Sure, their end product
was licensed under an open source license, but those were not really community
projects anymore.

The control of a specific party over the code is discouraging contributors to
participate: those are seen as free labor and are not on a level playing field
compared to contributors "on the inside", which really decide the direction of
the software. The only option for a disgruntled community is to do a costly
fork of the project, and fragment the limited resources available to work on
that topic. The most extreme case is the open core variant, where a company
maintains the basic functions of the software as an open source "community"
project but keeps advanced "enterprise" features under proprietary licenses.
This inevitably creates tension when a user wants to contribute back an
improvement (like security or scalability) that the controlling entity would
prefer to keep for its Enterprise edition. All this control ultimately hurts
the adoption and the success of the software.

OpenStack is an open source community that was started with the belief that a
community of equals, working together in an open collaboration, would produce
better software, more aligned to the needs of its users and more largely
adopted. It was therefore started from the first day as an open collaboration
willing to include as many individuals and organizations as possible, on a
level playing field, with everyone involved in designing and developing the
solution.

This was relatively novel: while a few venerable projects like the Linux kernel
were set up and perdured as truly open collaborations, most new projects in
2010 were just owned by a "main sponsor". This is why it was pretty important
for the individuals who participated in the OpenStack community to state in a
very concise way what they really meant by 'open'. It was also important to
clearly distinguish themselves from prevalent open core solutions like
Eucalyptus, which was then the only open source cloud infrastructure platform
available.

It was from these conditions that "The Four Opens" were born. The first public
mention of them was posted on the then-nascent OpenStack Wiki on June 28,
2010 [#fouropenswiki]_, before OpenStack was even publicly discussed or
announced. The titles of the Four Opens (Open Source, Open Design, Open
Development, Open Community) were set from that day. The content evolved a bit
over time on the Wiki, as implementation details rolled in (for example: public
code reviews, design summits, technical committee, lazy and consensus). The
Four Opens description is now maintained officially in the OpenStack governance
website [#fouropens]_ and followed by several projects in the open source
ecosystem.

They were instrumental in the success, the quality and the visibility of the
OpenStack software as well as the growth of the community from tens of
contributors to thousands over the course of a few years.

As this book will show how The Four Opens transform open source into open
collaboration that is essential to create open source software and other
artifacts by a group of individuals and organizations who have a set of common
goals and challenges they choose to solve together.

.. [#fourfreedoms] https://www.gnu.org/philosophy/free-sw.en.html
.. [#fouropenswiki] https://wiki.openstack.org/w/index.php?title=Open&oldid=9628
.. [#fouropens] https://governance.openstack.org/tc/reference/opens.html
