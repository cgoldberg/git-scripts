# git-scripts

#### A collection of scripts for working with [Git][git-home] and [GitHub][github-home]

All script are written in [Bash][bash-home] or [Python][python-home].

---

- Copyright (c) 2025 [Corey Goldberg][github-profile]
- Development: [GitHub][github-repo]
- License: [MIT][mit-license]

----

#### Contents:

- [**git-clean-untracked**](https://github.com/cgoldberg/git-scripts/blob/main/git-clean-untracked) (bash):
  - Delete untracked files and directories with confirmation
- [**git-contribs**](https://github.com/cgoldberg/git-scripts/blob/main/git-contribs) (bash):
  - Show contributor stats
- [**git-info**](https://github.com/cgoldberg/git-scripts/blob/main/git-info) (bash):
  - Show information about repository
- [**git-obliterate-repo**](https://github.com/cgoldberg/git-obliterate-repo/blob/main/git-info) (bash):
  - Delete untracked files, local/remote branches/tags, and all commit history
- [**git-prs**](https://github.com/cgoldberg/git-scripts/blob/main/git-prs) (bash):
  - Open GitHub Pull Requests URLs in a web browser
- [**git-score**](https://github.com/cgoldberg/git-scripts/blob/main/git-score) (python):
  - Show commit statistics
- [**git-stat**](https://github.com/cgoldberg/git-scripts/blob/main/git-stat) (bash):
  - Colorize status to indicate branch state
- [**git-sync**](https://github.com/cgoldberg/git-scripts/blob/main/git-sync) (bash):
  - Rebase all local branches in current repository from remote tracking branches
- [**git-syncrepo**](https://github.com/cgoldberg/git-scripts/blob/main/git-syncrepo) (bash):
  - Sync branch in remote fork with main branch in parent repo
- [**git-track-branches**](https://github.com/cgoldberg/git-scripts/blob/main/git-track-branches) (bash):
  - Create a local tracking branch for every remote branch
- [**git-whack-branches**](https://github.com/cgoldberg/git-scripts/blob/main/git-whack-branches) (bash):
  - Delete all local branches except default and current branch, even if not merged

----

#### Requirements:

- Git
- Bash
- Python
- jq

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
