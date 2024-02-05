# jfokus2024-talk

"Use Git Submodules Instead of Copying Your Config Files" - talk at JFokus 2024

> Our code bases typically contain a lot of files other than the source code. This can include config files for linters, code check tools, build scripts etc. When dealing with multiple code bases, a lot of these files are identical, possibly with slight differences that depend on the project name. If we copy these files, we end up in a situation where, if we modify one file, we have to manually make the same change in each repository. By placing these files in a separate repository, and using this as a submodule in the application repositories, we can manage this much easier.

The following repositories were used in the demo:

* https://github.com/samuelmurray/jfokus2024-app
* https://github.com/samuelmurray/jfokus2024-submodule

JFokus page:
https://www.jfokus.se/talks/1679

Git submodule documentation:
https://git-scm.com/docs/git-submodule