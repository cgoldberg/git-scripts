# git-scripts

#### A collection of scripts for working with [Git][git-home] and [GitHub][github-home]

All script are written in [Bash][bash-home] or [Python][python-home].

---

- Copyright (c) 2025 [Corey Goldberg][github-profile]
- Development: [GitHub][github-repo]
- License: [MIT][mit-license]

----

#### Contents:

- [**git-info**](https://github.com/cgoldberg/git-scripts/blob/main/git-info) (bash): Show info about local git repo
- [**git-score**](https://github.com/cgoldberg/git-scripts/blob/main/git-score) (python): Aggregate Git commit statistics
- [**git-stat**](https://github.com/cgoldberg/git-scripts/blob/main/git-stat) (bash): Colorize git status to indicate branch state
- [**git-sync**](https://github.com/cgoldberg/git-scripts/blob/main/git-sync) (bash): Rebase all local Git branches in current repo from remote tracking branches
- [**git-syncrepo**](https://github.com/cgoldberg/git-scripts/blob/main/git-syncrepo) (bash): GitHub remote repo sync
- [**git-track-branches**](https://github.com/cgoldberg/git-scripts/blob/main/git-track-branches) (bash): Create a local tracking branch for every remote branch

----

#### Requirements:

- Git
- Bash or Python

----

#### Usage:

- clone or download this repo
- add scripts to a directory on your `PATH`
- make scripts executable (i.e. `chmod +x git-info`)
- run a script from any directory in a local git repo.
  - you can call them by script name (i.e.: `$ git-info`)
    or through the Git executable (i.e.: `$ git info`)

[git-home]: https://git-scm.com
[github-home]: https://github.com
[github-profile]: https://github.com/cgoldberg
[github-repo]: https://github.com/cgoldberg/git-scripts
[bash-home]: https://www.gnu.org/software/bash
[python-home]: https://www.python.org
[mit-license]: https://raw.githubusercontent.com/cgoldberg/git-scripts/refs/heads/main/LICENSE
