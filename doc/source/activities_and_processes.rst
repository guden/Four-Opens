==================
Practical Examples
==================

The Four Opens is a set of principles to guide you when you build, support or
participate in an open source community to ensure a healthy and balanced
environment.

While there is no magic formula that would apply to all communities, there
are practices you can follow and steps you can take regardless of you being one
of the contributors, or if you work for an organization that supports the
project.

This chapter will give you examples and recommendations to build on based on
the experiences of the OpenInfra communities and the ecosystems around them. We
will cover the following areas:

- Common mission & goals
- Effective governance & leadership
- Diversity & Inclusiveness

Common Mission & Goals
----------------------
The idea behind openly-developed open source software is to share and work
together on tools and projects that provide solutions to common problems. While
having a shared challenge is a good start for collaboration, it cannot
guarantee a stable direction for the community in itself. This is why it is
crucial to define the common goals for the community and summarize them in a
strong mission statement.

A clear mission statement and goals are essential to create and maintain
balance between contributors, users and the ecosystem around a community. They
should be easy to discover to give a clear view of the community values and
direction to everyone - established and new contributors, adjacent communities,
users, and so forth.

It is important to spend time on making the mission statement and goals as
clear and simple as possible. In addition, the community can also define a long
term vision which describes the target they would like to reach. The vision can
serve as big picture to provide guidance for actions and decisions. However, as
both technology and the challenges are changing rapidly, it is worthwhile to
revisit the mission, goals and vision periodically to ensure they are still
accurate and update them if necessary.

This step should be completed while the community is in the forming phase, as
getting input and buy-in from everyone who is motivated to participate is key
to long term success. The advantage of developing the mission statement in the
early days is having fewer contributors who need to reach consensus through an
open discussion and process. As the community grows and evolves the process of
updating the mission statement and goals should also follow the same open
procedures, even if it seems harder at first.

A good example to explore is how the Zuul community worked and agreed on their
goals and mission. Project leaders first drafted example mission statements in
an etherpad [#f1]_, which was circulated to the public mailing list for
feedback and new ideas [#f2]_. The list of ideas from the etherpad was then put
to a Condorcet vote [#f3]_ for the same group of contributors to choose the
variant that resonated with most, which was: "To provide software and processes
to automate continuous integration, delivery, and deployment of interrelated
software projects in a secure manner using project gating."

Effective Governance & Leadership
---------------------------------
When you are working together with a group of people you will soon need
processes and governance to ensure smooth collaboration and operation.

Governance is the set of rules that the group follows in order to address
issues and make decisions that affect the whole community or some of the
sub-groups and to avoid decision apathy. Governance can also help to resolve
any conflicts and help reaching consensus where needed. In addition, having
formal bodies in a community to guide and deal with technical and community
related issues these bodies can also help with coordinating cross-community
outreach and interactions.

While you cannot anticipate all challenges that the community will need to
overcome and every governance body that they will need over time, you should
still encourage your community - that you are a part of or supporting - to put
a basic structure in place. This can help to avoid anarchy where you can hit
big road blocks and obstacles if you try to create an organizational structure
later as the community is starting to grow. The governance bodies should evolve
and grow with your community over time.

There are multiple models to choose from and you can find examples to these
within existing communities.

Projects often start as a one-person endeavor with no need of governance, and
from there can naturally evolve into a collaboration on which the initial
project creator retains full authority and become "benevolent
dictator for life" (BDFL) [#f5]_. You can look into the Linux kernel, as an
example to the BDFL model. Even though the Linux kernel became very successful,
this model has many risks that you need to take into account. If the project
leader loses interest or has another reason to leave the community, it can
enter governance limbo with no clear way forward and challenges to make
decisions the community agrees with (you can see the Gentoo or Python projects
as examples). The leader can also engage in toxic and in some cases abusive
behaviors that is hard to control and will affect existing contributors and
make it hard to on-board newcomers.

The solution to avoid the drawbacks of a BDFL model is to create governance
bodies, which are diverse groups within the community, that are responsible to
help and guide the community to work towards its mission to achieve its goals.

To build such framework, you should consider the following four rules:

Contributor-driven bodies
 People who are active participants of the community are the best skilled and
 positioned to become stewards. By building the governance bodies from the
 project contributors, you can ensure that they are representing the community
 that remains aligned with the leadership of the project.

 Without contributor-driven bodies and leadership, contributors will most
 likely gradually drift apart, to the point where they no longer feel like
 their leadership represents them. This can lead to making the disruptive
 decision to fork the project under a new, contributor-aligned governance,
 generally leaving the old governance body with a trademark and an empty shell
 to govern.

Allowing for replacement
 Nobody should be appointed for life. Processes should allow to revisit the
 governance bodies and elect new leaders and group members from the community
 by the community on a regular basis that is well publicized. This ensures that
 new views and ideas are brought into the project leadership.

 It can also help to avoid the burning out established leaders as well as
 encouraging new contributors to join and maintain the project if they have the
 opportunity to become one of the leaders over time.

Distinct groups call for distinct governance bodies
 As a community grows it often ends up having disjoint groups with little or
 no overlap between them. For example, these groups can be project teams, who
 work on different services that make the end product of the community. These
 project teams usually need a project leader and a stable group of people who
 ensure quality work and efficient processes around that team and service.

 Every group that is mainly standalone within a community needs to have its own
 governance body at that level.

Avoid vanity governance bodies
 In order to keep balance, the opposite of the former rule also applies. You
 should avoid overloading a community with governance bodies which typically
 results in making the community slower and less efficient. Once a community
 has an initial framework it needs to be carefully revisited if all the
 governing bodies are useful and necessary or if there is a need for a new
 group for an area that is yet uncovered and therefore not operating
 efficiently. The opposite is also true as there is no point in having a
 governance body where there is nothing to govern and no decision is needed. It
 is crucial to keep balance to focus on helping the community to operate as
 opposed to drown in heavy and complicated processes or have a governance body
 just for people to hold power.

There is no one-size-fits-all implementation of these basic rules that would
work for every project. The size of the project is a critical factor to take
into consideration, where larger communities may call for a multiple-level
structure to properly balance autonomy and consistency.

Choosing the project stewards could also be a challenging task, but there are
popular ways to build the governing bodies. When a community is forming and
people don't necessarily know each other yet, it can be hard to make a decision
that involves the whole community. A common practice is to appoint the first
group or groups of leaders from the people who launched the project.

After a first term -that often spans from 6-month to a year- when the community
is operational they are most often switch to an election-based process to find
new members to the governance bodies. Popular choices to make:

- Use a ranking vote mechanism (Condorcet, STV...)
- Condorcet is known to favor consensual candidates over faction candidates
- Staggered elections (replacing half the seats at each election) ensures some
  leadership continuity with the opportunity to introduce new members and
  refresh the group
- Limits in the number of seats potentially held by employees from a single
  organization are usually a good way to sidestep governance gaming

Governance bodies should ideally only make consensual decisions, but when that
proves impossible and a decision needs to be made, this can be resolved by
holding a formal vote. You can also consider having odd numbers of members in
the governance bodies to avoid having to give anyone a tie-breaking specific
power.

Diversity & Inclusiveness
-------------------------
Open source practices are all about open collaboration without limits and
boundaries, but it's much easier said than done.

A community has to be an inclusive and safe environment to participate in for
everyone, regardless of their circumstances and characteristics, such as
gender, sexual orientation, disability, physical appearance, body size, race,
nationality or religion. In order to create such environment, you need to
create and maintain a culture within the community, which requires work and
conscious effort from the very beginning. And along with culture and human
behavior, the community also needs inclusive processes.

There are several steps that you can take to create a friendly, welcoming and
accessible environment for everybody no matter who and where they are. This
section mentions a handful of these for you to consider to apply in the
community you support or participate in.

Code of Conduct
+++++++++++++++
While we all expect people to bring their best behavior and intentions, there
are cases when people's actions and interactions go beyond a limit and become
harmful. The community needs to be able to define their standards to state
their values, rules and expectations with regards to how people are expected to
behave and treat each other. The document that describes these items is called
a Code of Conduct.

While it may seem self explanatory, and, with that, unnecessary to have from
the launch of the project, it is a crucial step and serves as the foundation to
create the open and inclusive culture and environment that is desired for every
open source community.

There are several well-crafted Code of Conduct documents that you and your
community can use as a basis to create your own with giving recognition to the
original document. As an example, portions of the Open Infrastructure
Foundation's Code of Conduct were derived from the PyCon Conference Code of
Conduct.

To take this a step further, defining your values and expectations is not
enough without a process to be able to enforce it and report violations. It is
very important to address the creation of such process along with the Code of
Conduct document. Having a process to report violations in a clear and
anonymous way and having a similarly clear resolution path are key to make your
community a safe environment for everyone in it. Violating the code of conduct
always have emotional implications and therefore being able to resolve the
conflict as soon as possible is in the best interest of both the community as
well as the individuals involved in the incident.

Advocacy and Support
++++++++++++++++++++
Having a Code of Conduct and continuously putting effort into creating a
friendly and welcoming culture for the project are just the first steps, but
they are not necessarily enough to build a truly diverse community. People,
especially in under represented groups, can have a hard time when they start to
participate in a community that is new to them because of bad experiences
elsewhere or just because of being intimidated to join a larger group of people
who they don't know.

Many communities recognized these challenges and contributors are forming
groups to put more focused efforts into helping newcomers to join a project as
well as to ensure that the community is a safe and friendly environment for
everyone.

The OpenStack community recognized this need early on and formed a group called
Women of OpenStack (WOO), where they set it to their mission to help women in
technology to become part of this project. The group had a mailing list and a
channel on IRC in order to be reachable for anyone in need and they were also
meeting on a regular basis to find ways to advocate for women, and help them
with their first steps and contributions. While the name might suggests, the
group was open for anyone to join, regardless of their gender, who was wanted
to participate in reaching the group's mission and goals. The WOO group also
organized gatherings at OpenStack and some other events as well to reach out to
more and more people in need of their help and support.

Over time the WOO group transformed into the Diversity and Inclusion Working
Group to broaden the group of people to reach out to, as there are many under
represented groups in tech who need to find their voices and freedom to be able
to do what they are passionate about.

Inclusive Processes
+++++++++++++++++++
When we talk about diversity it is easy to focus on the bigger movements that
consider factors like gender, race, religion, and so forth. But being inclusive
is even broader than that.

Especially in case of larger global communities, simple things like time zones
and spoken language can prevent someone from participating. It is very
important that both the community as a whole as well as individuals in it are
conscious about these factors when they build their processes and define their
ways to collaborate.

To give a simple example, if your community relies on meetings for strategic
discussions and to make decisions that means that you are excluding all the
people from the decisions making process who are unable to attend these
gatherings for any reason. This violates many pillars of the Four Opens, as the
people who are unable to participate in these discussions cannot make their
voices heard and participate and have much less chance to ever rise to
leadership positions, even if they are still motivated to do so.

The OpenInfra communities rely a lot on their mailing lists to ensure that the
discussions that concern project teams or the whole community can reach
everyone before decisions need to be made. It is a conscious decision to
provide enough time and accessible channels for everyone to weigh in regardless
of where they are and what is their native language. On top of mailing lists
you can also use review tools like Gerrit or GitHub to publish items like
design documents or resolutions that you need a decision on. These tools
provide the possibility for everyone to read the problem statement, even
without creating a user and sign in, and to join the discussion which is also
logged to keep a conversation history.

Diversity is also represented in the ways how people can contribute. Even when
we talk about software development communities, not everyone is a software
developer who participates. You need documentation for the project, a website
where you can share information, people who report issues with the software,
speak at or organize events and many other things that are not about code
development, but essential for the long term success of your project. If you
only focus on and favor the technical contributors, the community will not be
an inclusive place anymore to a lot of people whose knowledge and experience
are key.

Being inclusive can be very challenging due to a lot of circumstances that a
community has to overcome. But it has to be a choice from the first day to
create a culture, where inclusivity is a principle that turns into action every
day, which includes the processes that the community creates to help them to
collaborate without boundaries.

.. rubric:: Footnotes

.. [#f1] https://etherpad.openstack.org/p/zuul-mission
.. [#f2] http://lists.zuul-ci.org/pipermail/zuul-discuss/2018-May/000394.html
.. [#f3] https://civs.cs.cornell.edu/cgi-bin/results.pl?id=E_708e8e18e160cdcf
.. [#f4] https://superuser.openstack.org/articles/open-infrastructure-community-contributor-awards-denver-summit-edition/
.. [#f5] https://en.wikipedia.org/wiki/Benevolent_dictator_for_life
