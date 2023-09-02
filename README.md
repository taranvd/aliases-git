## Git Aliases

### Basic Git Commands

- `g` - Alias for `git`
- `ga` - Alias for `git add`
- `gaa` - Alias for `git add --all`
- `gapa` - Alias for `git add --all`
- `gau` - Alias for `git add --update`
- `gav` - Alias for `git add --verbose`
- `gap` - Alias for `git add --patch`

### Git Apply

- `gapt` - Alias for `git apply`
- `gb` - Alias for `git apply --3way`

### Git Branch

- `gba` - Alias for `git branch`
- `gbd` - Alias for `git branch -a`
- `gbda` - Alias for `git branch -d`
- `gbD` - Alias for complex branch cleanup command (see documentation)
- `gbl` - Alias for `git branch -D`

### Git Blame

- `gbnm` - Alias for `git blame -b -w`

### Other Branch Commands

- `gbr` - Alias for `git branch --no-merged`
- `gbs` - Alias for `git branch --remote`

### Git Bisect

- `gbsb` - Alias for `git bisect`
- `gbsg` - Alias for `git bisect bad`
- `gbsr` - Alias for `git bisect good`
- `gbss` - Alias for `git bisect reset`
- `gc` - Alias for `git bisect start`

### Git Commit

- `gc!` - Alias for `git commit -v`
- `gcn!` - Alias for `git commit -v --amend`
- `gca` - Alias for `git commit -v --no-edit --amend`
- `gca!` - Alias for `git commit -v -a`
- `gcan!` - Alias for `git commit -v -a --amend`
- `gcans!` - Alias for `git commit -v -a --no-edit --amend`
- `gcam` - Alias for `git commit -v -a -s --no-edit --amend`
- `gcas` - Alias for `git commit -a -m`
- `gcasm` - Alias for `git commit -a -s`
- `gcsm` - Alias for `git commit -a -s -m`
- `gcb` - Alias for `git commit -s -m`

### Git Checkout

- `gcf` - Alias for `git checkout -b`

### Git Config

- `gcl` - Alias for `git config --list`

### Git Clone

- `gccd` - Alias for `git clone --recurse-submodules`
- `gclean` - Alias for `git clone --recurse-submodules "$@" && cd "$(basename $_ .git)"`

### Git Clean

- `gcm` - Alias for `git reset --hard && git clean -dffx`

### Git Checkout Branch

- `gcd` - Alias for `git checkout $(git_main_branch)`
- `gcmsg` - Alias for `git checkout $(git_develop_branch)`

### Git Commit Messages

- `gco` - Alias for `git commit -m`
- `gcor` - Alias for `git checkout`
- `gcount` - Alias for `git checkout --recurse-submodules`

### Git Shortlog

- `gcp` - Alias for `git shortlog -sn`

### Git Cherry-Pick

- `gcpa` - Alias for `git cherry-pick`
- `gcpc` - Alias for `git cherry-pick --abort`
- `gcs` - Alias for `git cherry-pick --continue`

### Git Signing

- `gd` - Alias for `git commit -S`

### Git Diff

- `gd` - Alias for `git diff`
- `gdca` - Alias for `git diff --cached`
- `gdcw` - Alias for `git diff --cached --word-diff`
- `gdct` - Alias for `git diff --cached --word-diff`
- `gds` - Alias for `git describe --tags $(git rev-list --tags --max-count=1)`
- `gdt` - Alias for `git diff --staged`
- `gdnolock` - Alias for complex diff command (see documentation)
- `gdup` - Alias for `git diff @{upstream}`
- `gdv` - Alias for complex diff command (see documentation)
- `gdw` - Alias for `git diff --word-diff`

### Git Fetch

- `gf` - Alias for `git fetch`
- `gfa` - Alias for `git fetch --all --prune`

### Git List Files

- `gfg` - Alias for complex list files command (see documentation)

### Git Fetch Origin

- `gfo` - Alias for `git fetch origin`

### Git GUI

- `gg` - Alias for `git gui citool`
- `gga` - Alias for `git gui citool --amend`

### Git Push

- `ggf` - Alias for `git push --force origin $(current_branch)`
- `ggfl` - Alias for `git push --force-with-lease origin $(current_branch)`

### Git Pull

- `ggp` - Alias for `git pull origin $(current_branch)`
- `ggpnp` - Alias for complex pull command (see documentation)

### Git Pull Current Branch

- `ggpull` - Alias for complex pull command (see documentation)
- `ggpur` - Alias for `git pull --rebase origin $(current_branch)`

### Git Push Current Branch

- `ggpush` - Alias for complex push command (see documentation)
- `ggsup` - Alias for `git branch --set-upstream-to=origin/$(git_current_branch)`

### Git Pull Rebase

- `gpsup` - Alias for `git pull --rebase origin $(current_branch)`

### Git Push Set Upstream

- `ghh` - Alias for `git push --set-upstream origin $(git_current_branch)`

### Git Help

- `gignore` - Alias for `git help`

### Git Update Index

- `gignored` - Alias for `git update-index --assume-unchanged`

### Git List Files (Lowercase)

- `gignored` - Alias for complex list files command (see documentation)

### Git SVN Dcommit Push

- `git-svn-dcommit-push` - Alias for complex SVN dcommit and push command (see documentation)

### Gitk

- `gk` - Alias for `git
