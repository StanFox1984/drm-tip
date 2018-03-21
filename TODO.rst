TODO
====

dim
---

- extract the integration tree logic and make it generally useful, maybe for a
  drm-integration tree ...
- add option to check-patch to check stdin
- integrate ninja-check? Or too much checkers considered harmful?
  https://lists.linuxfoundation.org/pipermail/ksummit-discuss/2014-May/000554.html
- add patchwork Link: also after manually resolving conflicts in drm
  apply-resolved
- pull in dim extract-tags tool from Ville
- allow dim rebuild-nightly to pull branches from local trees in dry-run mode.
  This is useful to confirm a backmerge is indeed correct, by comparing the
  resulting -nightly with the old one. Current the branch must be pushed out
  first for rebuild-nightly to pick it up, which means the merge can't be
  fixed any more.
- apply-resolved fails to add the Link: tag.
- Harvest and add Cc labels to all authors when tagging a branch
- Parse Cc labels from tag body and add as email headers when sending pull requests

qf
--

- get better at preventing and cleaning up a mess when switching branches
  while there's still applied quilt patches around ...
- combine quilt annotate and git blame into one tool
- use the index a bit more to e.g. stage all applied quilt patches, then use
  the output of git diff to refresh a quilt patch
- use git commit-tree and git write-tree in the setup code instead of the
  current high-level hacks
- track/restore the topmost patch maybe?
- synchronize quilt notes in qf push and qf fetch
