Github collaboration workflow demo
==================================

## Initial Steps:

1. Fork the repo on github
2. Clone to your machine
3. Work against master
4. Commit code to master
5. Push master to origin
6. Issue a pull request against upstream master

Most of the time merges will be resolved automatically via a fast forward.

### Resolving conflicts

Sometimes, there will be conflicts. Conflicts occur when two people change the same lines of a file.

* The person opening the pull request, shouldn't open the pull request until they resolve the conflicts on their machine

To add the upstream repo:
```
$ git remote add upstream [upstream/blessed repo url]
```

* [Resolving conflicts](https://help.github.com/articles/resolving-a-merge-conflict-from-the-command-line/)
