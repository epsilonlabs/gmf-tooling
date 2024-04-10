# GMF Tooling Update Site

Following the [termination of the GMF Tooling project](https://gitlab.eclipse.org/eclipsefdn/emo-team/emo/-/issues/593), the update site that used to reside on http://download.eclipse.org/modeling/gmp/gmf-tooling/updates/releases has disappeared.

This repository hosts a copy of the final version of the GMF Tooling update site, extracted from the `updates/releases-3.3.1a` folder of the project's [tarball](http://archive.eclipse.org/archived_projects/gmf-tooling.tgz) so that tools that depend on GMF Tooling (e.g. [Eugenia](https://eclipse.dev/epsilon/doc/eugenia/)) can still be installed without needing to download/extract the entire tarball.

To install GMF Tooling from this update site, please point Eclipse (`Help -> Install New Software`) to:

```
https://github.com/epsilonlabs/gmf-tooling/raw/main/
```