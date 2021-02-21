===========
Open Source
===========

The most fundamental principle, historically reaching back to the Four Freedoms
of the Free Software Foundation, is Open Source. Any software developed under
the guidance of the Four Opens must be released under an open source license.
It means that anyone should be able to study a program, modify it, and
redistribute either the original or the modified version so that others may
benefit from their work. But the Four Opens is much more than just access to
the source code, as you will see in the following chapters.

As discussed earlier, free and open access to the source code is just just one
factor, but it doesn't ensure anything about the quality, usability and
scalability of that code. Open Source also entails the possibility to openly
collaborate on any enhancement or new development direction to the software,
and it should not be limited in features or performance to enable a company's
business model. Open Core is a collaboration model where some of the
functionality is open source, while there are features that are withheld by a
company controlling the open source project, allowing to sell a proprietary
"Enterprise Edition".

While the Open Core model is compatible with open source and might seem like a
good model at first, it has a lot of shortcomings that prevents you from
building a healthy and balanced community around it. It cannot engage
participants from other vendor companies long term as not all functionality is
available to add to the community version of the software. This can lead to
copy the existing code base and develop it further under a different name and
maybe license, this is what is called forking. This behavior creates
fragmentation in the community that can result in tension and unhealthy
environments.

Users of the open source edition of an Open Core software may fall into similar
traps, as they can be forced to purchase the Enterprise Edition to access extra
functionality that is only available there. This can result in lock-in, despite
of them originally choosing an open source solution, which then didn't give
them the freedom it was supposed to. This can lead them to the choice of
looking for a different community or solution overall.

The Open Core model always fails when a contributor eventually tries to add a
feature that is not supposed to be made available in the open source version
according to the company in control, who owns the productized version. This
circumstance leads to confusion, frustration and tension which undermines the
concept of open collaboration on a level playing field, which the Four Opens
are meant to ensure.

In addition, these enterprise features often fall in the groups of security or
scalability, which are desirable by all users.

The Open Source Principle in Practice
-------------------------------------

Open Source begins with the choice of license a community applies to its
project. In most cases, the communities supported by the Open Infrastructure
Foundation use v2.0 of the Apache License [#apachev2]_. It is:

- OSI approved [#OSI]_
- GPLv3 compatible [#GPLv3]_
- DFSG compatible [#DFSG]_

This license meets the requirements of being able to modify and redistribute
the work. It includes a number of provisions that also protect end-users by
granting copyright and patent licenses to all, while limiting liability to the
original copyright holder. This patent protection is one of the distinguishing
features in comparison to other open source licenses, like the MIT License.

In practice, regardless if you are an individual or corporate contributor, you
need to understand the consequences of contributing code to an Apache Licensed
project, particularly the granting of copyright and patent licenses to all
users of the software. To acknowledge this, many projects require that all
contributors sign a "Contributor License Agreement" (CLA) [#OSCLA]_ or
"Developer Certificate of Origin" (DCO).

Typically, a CLA is a stronger statement, attesting that you, as a contributor,
have a right to submit work to the project and that they are granting copyright
and patent licenses in accordance with the Apache License along with your
submissions.

A DCO, on the other hand, is a bit lighter weight and is more of a statement
(rather than a license) that you, as developer, are indeed authorized to submit
changes to the project and understand that your contributions will be used in
accordance with the license.

A CLA, being a stronger document, is also often considered to be a barrier to
entry. A DCO, in contrast, lowers the barrier to entry by removing the
requirement to consent to a legal document [#CLAvDCO]_.

Apache 2.0 is very liberal in allowing companies to modify and use the code in
any way they want, and doesn't place requirements to release changes (although
it doesn't prohibit them from doing so). This, along with the patent
protections of the license, is one of the reasons why it is so popular. It has
also been used in practice since 2004, and is fairly well understood amongst
the corporate and open source legal communities.

This liberal view on modification does have some downsides, though. It becomes
very easy for companies to withhold enhancements that would be beneficial to
the wider community, or to make changes to their version of the software that
breaks interoperability. While the license doesn't address these directly,
there are guard-rails that a project can put in place to mitigate these risks.

Trademark programs based on interoperability or conformance testing are one
such tool. The Open Infrastructure Foundation uses such a program. In order to
qualify for the trademark, a product can not modify API code (thus adding a
stronger modification restriction than provided by the Apache License), and it
must successfully demonstrate compatibility by passing a suite of
interoperability tests, run against the public API of the product. In this way,
the scope of modifications is limited.

Furthermore, in case of fast-evolving infrastructure software, it's worth
noting that keeping local changes private is not a great long-term strategy.
Maintaining a delta between code running in production and fast-evolving
upstream open source code is very costly, and gets more difficult as time
passes. Technical debt adds up quickly to a point where paying it back is
impossible. Engaging upstream to propose your local improvements and finally
getting most of them in the open source project itself is the only sustainable
way forward over the long run.

References
----------
.. [#OSI] https://opensource.org/licenses/alphabetical
.. [#GPLv3] https://www.gnu.org/licenses/license-list.html#apache2
.. [#DFSG] https://en.wikipedia.org/wiki/Debian_Free_Software_Guidelines
.. [#apachev2] https://www.apache.org/licenses/LICENSE-2.0
.. [#OSCLA] https://wiki.openstack.org/wiki/OpenStackAndItsCLA
.. [#CLAvDCO] https://opensource.com/article/18/3/cla-vs-dco-whats-difference
