================
Open Development
================

Open Development is the next pillar as well as the next step after establishing
the Open Design principle. Similarly to the former steps, you also need a
transparent and inclusive development process that enables everyone to
participate as equals on a level playing field.

The contributors of your community need to have access to every step of the
process. This means that the process needs to be documented and accessible for
everyone including established contributors and newcomers. You need to use
tools and services that are also available to all participants to use in order
to perform the required steps of the process.

The community should not differentiate between contributions depending on the
affiliation of the person who authored or committed that change. The review
process needs to be open with history so requests and decisions can be accessed
later. While accepting contributions can look subjective you need to put all
the effort into documenting criteria, guidelines - to write code or
documentation - and processes to ensure the most objective process possible.
In addition, you can also put a lot of emphasis on automation, such as testing
- unit, functional, integration tests and more - in case of source code.

Reviewing contributions should be available, and encouraged, to everyone who is
interested in the project, even if the final decision can be made only by a
subset of contributors. These contributors -called core reviewers, committers,
etc-, should be members of the project leadership and elected by the fellow
community members based on merit.

The open development process opens up the avenue for newcomers to become
seasoned contributors and then take on leadership positions, if that is
something that they desire. Besides contributing new ideas and functionality,
it is very important to demonstrate how much one cares about the project,
including the quality of the software as well as the processes used to create
and maintain it. You can become part of the community by reviewing
contributions, propose new ideas, fix issues and participate in the community's
communication channels, like mailing lists, meetings, and so forth.


Open Development Process Examples
---------------------------------

The OpenStack community is a large group of contributors with multiple project
teams who've been actively practicing and evolving their development processes
to make it more efficient and inclusive.

The community is following a set of metrics and guiding principles to evaluate
a code or documentation change:

- Correctness: code changes need to have corresponding tests to ensure it works
  as specified
- Quality Assurance: the code has test cases to ensure smooth integration with
  other services and does not introduce regression
- Documentation: a new feature needs to be properly documented, including
  API documentation and configuration options
- Purpose: the code change should implement a bug fix or new functionality as
  previously identified and discussed as part of the open design process

The OpenStack community prioritized automation from the beginning to ensure the
quality of the code as well as an open development process. Code changes go
through multiple rounds of automated testing where a change cannot be approved
without a successful test run. Once a change is approved by the core reviewers
it goes through one more round of testing. If that is successful, the change
gets merged into the project's code base. It is very important to note, that
the last entity who votes on the change is the tool that executes all the
applicable test cases.

The community is actively working on their contributor focused documentation
that captures the development processes and tools that are used throughout all
the phases. This ensures that everyone can gain the knowledge to be able to
contribute and follow the same guidelines to ensure a level playing field.
