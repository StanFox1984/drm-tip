===============
 Commit Access
===============

The drm-misc and drm-intel repositories operate in a maintainer/committer model
with a large pool committers who can push patches in accordance with the stated
merge criteria, and maintainers handling pull requests, topic branches, merges,
and so on.

This document outlines the requirements for becoming a committer.

drm-misc
--------

See :ref:`drm-misc`.

drm-intel
---------

Criteria
~~~~~~~~

Commit rights will be granted to anyone who requests them and fulfills the
following criteria:

- Has contributed at least 25 patches to i915 driver that have already been
  merged upstream. Most of the patches must be non-trivial, not just simple
  spelling or style fixes or code movement.

- Has reviewed at least 25 patches from other developers to i915 driver that
  have already been merged upstream. Again, most of the reviewed patches must be
  non-trivial.

- Are actively participating in discussions about their work and areas of
  expertise on the project communication channels (the intel-gfx mailing list,
  #intel-gfx freenode IRC channel, and freedesktop.org bugzilla).

- Has been active in the past year (at least some commits or reviews on i915
  driver).

- Will be regularly contributing further patches. This includes regular
  contributors to other parts of the open source graphics stack who only do the
  occasional patch within i915 itself.

- Agrees to use their commit rights in accordance with the documented merge
  criteria, tools, and processes.

The above criteria are in place to encourage and require committers are actively
and broadly engaged upstream, and that they are acquainted and comfortable with
the open collaboration model we have. To ensure the committers have enough
experience to gauge reasonably well how much review a patch needs, and whether
it needs acks from domain experts or maintainers before pushing.

Access Request
~~~~~~~~~~~~~~

Apply for an account (and any other account change requests, including commit
rights if you already have an account) through

https://www.freedesktop.org/wiki/AccountRequests/

Maintainer acks are required to confirm commit rights. Please ping the
maintainers if your request is stuck.

Maintainers may rate limit adding new committers to ensure there's enough
bandwidth to properly support ramp-up on the tools and processes. In this case,
the maintainers will pledge to add at least two new committers per month,
loosely prioritized based on commits, reviews, and in-flight patches.

Committers are encouraged to request their commit rights get removed when they
no longer contribute to the project. Commit rights will be automatically revoked
after a year of inactivity (no commits or reviews). Commit rights will be
reinstated when they come back to the project.

Maintainers and committers should encourage contributors to request commit
rights.

Code of Conduct
~~~~~~~~~~~~~~~

Please be aware the freedesktop.org Code of Conduct also applies to i915:

https://www.freedesktop.org/wiki/CodeOfConduct/

See the MAINTAINERS file for contact details of the i915 maintainers.

Abuse of commit rights, like engaging in commit fights or willfully pushing
patches that violate the documented merge criteria or process, will also be
handled through the Code of Conduct enforcement process. Violations may lead to
temporary or permanent account or commit rights suspension according to
freedesktop.org umbrella rules.
