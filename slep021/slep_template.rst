.. _slep_021

=============================
SLEP021 Simplified Governance
=============================

:Author: Christian Lorentzen
:Status: Draft
:Type: Process
:Created: 2022-02-1
:Resolution: TBD <url> (required for Accepted | Rejected | Withdrawn)

Abstract
--------

The governance structure gets more democratic elements and only three different roles are established.


Detailed description
--------------------

The governance document of scikit-learn,
https://scikit-learn.org/stable/governance.html#governance,
gets the following revisions:

   1. Add the word democratic.
   2. Establish 3 different roles:

      - contributor
      - core contributor with voting rights, i.e. core developer is replaced by core
          contributor
      - member of the technical committee which has to be a core member (unchanged)

   3. Prolong core contributor voting period from 1 to 2 weeks.


1. Add a bit more democracy - first by words
............................................

Change

"This is a meritocratic, consensus-based community project."

into

"This is a meritocratic, consensus-based community project with democratic elements."

2. Roles
........

There are three basic roles.

**Contributors**
"Contributors are persons who contribute in concrete ways to the project, e.g. they
invest time and energy to improve the project for the greater community. Anyone can
become a contributor, and contributions can take many forms - be it coding,
reviewing code, communications, organization, triaging, ... - as detailed in the
contributors guide.""

**Core Contributor**
Change "core developer" to "core contributor" everywhere. Core contributors are defined
as:

"Core contributors are persons who have shown that they are dedicated to the continued
development of the project through ongoing engagement with the community.
They have shown they can be trusted to maintain scikit-learn with care.
Core contributors are expected to invest continued time and energy in the project.
This includes selectively (not cumulatively):

  - Ensure the maintenance of scikit-learn
  - Help other contributors to engage in the project, and carry on with their project
    related activities.
  - Conduct public relations work
  - Triage github issues and pull requests
  - Review code
  - Contribute code
  - Create a development roadmap

Therefore, core contributors are given the following rights:

  - Call for votes and cast votes according to the decision making, see below.
  - Be involved in deciding major changes to the API and the governance.
  - Direct access to the project's GitHub repository and joining as organization member
    in the scikit-learn GitHub organization.
  - Cast vote for, i.e. approve, or cast a vote against pull-requests.
  - Merge pull-requests.

New core contributors can be nominated by any existing core contributors.
Once they have been nominated, there will be a vote by the current core contributors.
Voting on new core contributors is one of the few activities that takes place on the project's private management list.
While it is expected that most votes will be unanimous, a two-thirds majority of the
cast votes is enough. The vote needs to be open for at least 2 weeks.

Core contributors that have not resonably contributed to the project in the past 12
months will be asked if they want to become emeritus core contributors and recant their
commit and voting rights until they become active again.
The list of core contributors, active and emeritus (with dates at which they became
active) is public on the scikit-learn website."


Discussion
----------

[SLEP019](https://scikit-learn-enhancement-proposals.readthedocs.io/en/latest/slep019/proposal.html) This section may just be a bullet list including links to any discussions
regarding the SLEP:

- This includes links to mailing list threads or relevant GitHub issues.


References and Footnotes
------------------------

.. [1] Each SLEP must either be explicitly labeled as placed in the public
   domain (see this SLEP as an example) or licensed under the `Open
   Publication License`_.

.. _Open Publication License: https://www.opencontent.org/openpub/


Copyright
---------

This document has been placed in the public domain. [1]_
