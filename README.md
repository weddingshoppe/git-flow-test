# Git Flow Test repository

### Version: 0.2.0

* I've added newFeature1 using git-flow
  * This was added in a second local commit for newFeature1

* for feature 2, I will test squashing the feature commits
  * it seems that if I pass `-r` that it will rebase instead of merge when I `git flow feature finish -r feature2`
  * so that also didn't work.  it rebased but didn't squash.
    * based on this issue, I'll now try `--squash` with `git flow feature finish`
    * this is the content for my second commit for the squash-test feature