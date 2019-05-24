# v22.0.0 (2016-09-30)

- Fixed `grim` alias to leverage `gri` functionality.
- Fixed use of `break` in case statements within while loops.
- Added Git 2.9 `core.hooksPath`.
- Added Git 2.9 global configuration changes.
- Added Git hook support for printing duplicate messages.
- Added Git hook support for printing error messages.
- Added Git hook support for printing warning messages.
- Added Git pre-push commit hooks for checking source comments.
- Added GitHub repository file processing option.
- Added `gcfp` function.
- Added `gdo` alias for diffing conflicting files.
- Added `gemdep` function for finding gem dependencies.
- Added `glean` alias.
- Added `gstats` and `gstatsa` functions for Git project stats.
- Added `hbsu` alias for performing Homebrew software updates.
- Added `pas` Pragmater gem alias for adding frozen string literal pragmas.
- Added `rew` function "custom" option.
- Added `rew` function PostgreSQL database support.
- Added `rew` function Rails Dummy Template support.
- Added `rmde` alias for removing empty directories.
- Added aliases for starting and stoping Elasticsearch.
- Added diff-so-fancy support to Git global config.
- Added direnv aliases.
- Updated Git hooks to use warning and error messages.
- Updated `fms` alias to ignore environment file.
- Updated `gbdm` function so that it deletes remote and local merged branches.
- Updated `rew` configuration to use Rails 5 settings.
- Removed "Total" prefix from `gount` function.
- Removed .irbrc pry-remote, pry-rescue, and pry-stack_explorer gems.
- Removed Ember.js aliases.
- Removed Git global config for repository initialization.
- Removed Git hook delete functions.
- Removed Rails API template generation option.
- Removed Tocer aliases.
- Removed superfluous comments.
- Refactored Git config global settings.
- Refactored calculating Git stash count to private function.
- Refactored git last tag info to private function.

# v21.0.0 (2016-04-30)

- Fixed .bashrc program loading.
- Added .ruby-version template.
- Added GPG .bashrc settings.
- Added `berc` alias for `bundle exec rake console`.
- Added `besp` function for RSpec profiling.
- Added `bs` alias for `bundle show`.
- Added `gync` function to syncing with remote Git repository.
- Added `rbi` alias for `ruby-install`.
- Added chruby support.
- Added screencast tutorial to README.
- Updated .bashrc to ensure Homebrew analytics are always disabled.
- Updated Git blame aliases/functions to dig deeper into Git history.
- Updated Git log format to use short commit SHA.
- Updated `gtail` function to use short Git commit SHA.
- Removed ".env.sample" and "coverage" from .gitignore.
- Removed Capistrano support.
- Removed Ruby RDoc aliases.
- Removed `bashv` alias.
- Removed `bbr` alias.
- Removed `cinv` alias.
- Removed `ez` alias (use `ze` instead).
- Removed `msv` alias.
- Removed `rbest` alias (use `rbp` instead).
- Removed `rserv` function (use `rbs` instead).
- Removed `rua` function (use `rbua` instead).
- Removed `rva` function (use `rbva` instead).
- Removed `sv` function.
- Removed `tocv` alias.
- Removed rbenv support.

# v20.1.0 (2016-04-10)

- Fixed `gemcli` alias output.
- Fixed `rew` function documentation to describe branch option.
- Fixed extra pipe (|) showing up in Pry prompt.
- Added Git grep count to global configuration.
- Added `gcd` alias (for debugging Git configuration settings).
- Added `gpob` function.
- Added `grim` alias for Git interactive `master` branch rebasing.
- Added direnv support.
- Added untracked cache to Git global configuration.
- Updated .gitconfig to only use config for user name and email.
- Updated GitHub issue and pull request templates.
- Updated Milestoner `mse` alias to use new edit command.
- Updated Rubocop global configuration.
- Refactored Git local and remote branch deletion.
- Refactored IRB prompt keys and variables.

# v20.0.0 (2016-03-20)

- Fixed .pryrc template errors when loading missing gems.
- Fixed Git branch switch/delete functions for branches with pathnames.
- Fixed `groot` function so it works with Git worktrees.
- Fixed `hbug` alias to always force openssl link.
- Fixed contributing guideline links.
- Added .npmrc template.
- Added Elm aliases.
- Added Git global config single key interaction.
- Added GitHub issue and pull request templates.
- Added GitHub open pull request option to `gh` function.
- Added Rubocop global configuration.
- Added Ruby Console Kit method source location helper.
- Added Ruby Console Kit search method.
- Added `bcg` function for configuring Bundler with local gems.
- Added `besb` function for RSpec Bisect.
- Added `besd` function for debugging intermittent RSpec failures.
- Added `gbna` function for Git branch numbers of all projects.
- Added `gbsa` function for switching branches across multiple projects.
- Added `gemcli` alias for listing CLI gems only.
- Added `gemcr` alias for opening gem credentials in default editor.
- Added `ghpra` function (a.k.a GitHub Pull Request -- all).
- Added `gwa` "r" option for adding remote branches.
- Added `gwd` function (a.k.a. Git Worktree Delete).
- Added `gwl` alias for `git worktree list`.
- Added `rva` function for printing Ruby versions.
- Added `tciec` function for Travis CI Code Climate encryption.
- Added `tcies` function for Travis CI Slack encryption.
- Updated .bashrc history settings.
- Updated .gemrc to be linkable and deletable.
- Updated .inputrc settings to for forward/backward history completions.
- Updated README Table of Contents.
- Updated `gcama` function to launch default editor for commit message.
- Updated `gcap` to use same commit behavior as `gcaa` function.
- Updated `gwa` function to use "l" for adding local branches.
- Updated run script documentation.
- Updated to Code of Conduct, Version 1.4.0.
- Removed .irbrc console kit http code and symbol support.
- Removed IRB `ConsoleKit` object (use "CK" instead).
- Removed Priscilla gem support.
- Removed Ruby patch info from .pryrc template.
- Removed `besb` alias.
- Removed `gbna` function (use `gbla` instead).
- Removed `gcama` function (use `gcaa` instead).
- Removed `gdis` alias (use `grh` function instead).
- Removed `tcie` function (use `tciea` instead).
- Removed date/time from shell command prompt.
- Removed use of `grep` (replaced with `ag`).
- Removed use of `rescue nil` from .pryrc template.
- Refactored .irbrc template to use double quoted strings.
- Refactored Git function order.
- Refactored `gashs` function to use long options.
- Refactored `grh` alias as a function.
- Refactored `grs` alias as a function.
- Refactored launching of default editor to use long wait option.

# v19.0.0 (2016-01-02)

- Fixed Ruby IRB config with loading of gem enhancements.
- Added Bash alias section.
- Added `cype` function for colorized type.
- Added `gpf` alias for `git push `--force-with-lease`.
- Added `gpuo` alias (i.e. `git pull origin`).
- Added `gpuom` alias (i.e. `git pull origin master`).
- Added pry-state to Ruby IRB gem enhancements.
- Updated Git global config to enable mnemonicPrefix and renames for diffs.
- Updated `gup` function to optionally pull only.
- Updated `hbrb` alias to not use `ruby-build` HEAD.
- Updated global Git config to always rebase when pulling.
- Removed Rails 2.x.x function support.
- Removed Ruby IRB Rails 2.x.x prompt support.
- Removed Ruby IRB patch info prompt support.
- Removed `gpur` alias.
- Removed `gpuro` alias (use `gpuo` instead).
- Removed `gpurom` alias (use `gpuom` instead).
- Removed `ios` alias.
- Removed `toc` alias (use toc* aliases instead).

# v18.1.0 (2015-12-02)

- Fixed outdated reference links.
- Added "diff3" merge conflict style support to global Git configuration.
- Added Git auto-stash support when rebasing.
- Added Patreon badge to README.
- Added [Tocer](https://github.com/bkuhlmann/tocer) aliases.
- Added `bera` function for running default Rake tasks for all projects.
- Added `gli` function for Git Log (interactive).
- Updated to Code of Conduct 1.3.0.
- Updated Git commit template questions.
- Updated README with Tocer generated Table of Contents.
- Removed CW alias from global Git config.

# v18.0.0 (2015-10-14)

- Fixed "n" option in `gup` function code review.
- Fixed DNS aliases to flush and report stats correctly.
- Fixed Gemsmith aliases to use standard command syntax.
- Fixed restoration of Internal Field Separator (IFS).
- Added Git notes aliases.
- Added Git worktree support.
- Added `bashv` alias for printing Bash version.
- Added `cat` syntax highlighting.
- Added `dnsi` alias for printing current DNS info.
- Added `gile` function for Git file details/diff support.
- Added `gistory` function commit selection.
- Added git notes to git log details.
- Updated Git hook documentation.
- Updated `ghow` function to display commit details by default.
- Updated `glamel` function to support `gistory` features.
- Updated `gri` function to support branch names.
- Updated function documentation.
- Removed `catc` alias (use `cat` instead).
- Removed `glast` alias (use `ghow` function instead).
- Removed `glatest` alias (use `gbl` function instead).
- Removed `rpaths` alias.
- Removed `rprof` alias.
- Removed carriage return from current branch name.
- Removed relative "bin" folder being added to the path.
- Refactored Git log default format to common function.
- Refactored Git log line and details formats to private functions.
- Refactored RDoc aliases to use "tmp/doc/rdoc" directory.
- Refactored RailRoady `rr*` aliases as a single `rr` function.
- Refactored `erd` alias as a function.
- Refactored `gbc` function to use local variable.
- Refactored `glamel` to `glameh`.

# v17.0.0 (2015-09-27)

- Fixed `gri` function issue when no origin exists.
- Fixed `gtagd` function issues with no origin repository.
- Fixed bug with coping/pasting of special characters from pbpaste.
- Fixed calculation of commits since last tag.
- Added "api" option to `rew` function for build Rails API apps.
- Added Bashsmith generation to README history.
- Added RSpec section to aliases and functions.
- Added RailRoady alias section.
- Added Rails ERD alias section.
- Added Ruby Prof alias section.
- Added [Ember](http://emberjs.com) aliases.
- Added [Milestoner](https://github.com/bkuhlmann/milestoner) aliases.
- Added `bbr` alias for launching remote byebug debug session.
- Added `cinr` function for creating asciinema recordings.
- Added `gatch` alias for `git commit --patch`.
- Added `ghow` function for Git commit diff with log info.
- Added `grbs` alias for rebase skips.
- Added `gtagv` alias for tag verification.
- Added `toc` alias for generating table of contents.
- Added asciinema aliases.
- Added project name to README.
- Added table of contents to README.
- Added the `kilp` function.
- Added the `man` alias.
- Added user.signingkey to git config.
- Updated .gitignore to exclude PostgreSQL archive dumps.
- Updated Git branch listings to use author date.
- Updated `glt` alias to include tag author and message.
- Updated `mo` alias to use Marked 2.
- Updated git log related aliases and functions to show signature status.
- Updated shell prompt to only show Git email domain.
- Updated to Code of Conduct 1.2.0.
- Removed "r" prefix from Rubocop aliases.
- Removed "vendor" folder from Git hooks search.
- Removed GitTip badge from README.
- Removed Ruby Test::Unit related aliases.
- Removed `bern*` aliases (use `notes*`) instead.
- Removed `gra` alias (use `grba` instead).
- Removed `grc` alias (use `grbc` instead).
- Removed `rass*` aliases (use `ass*`) instead.
- Removed `rdb*` aliases (use `db*` instead).
- Removed `rebundle` alias.
- Removed sort and unique support when finding commits since last tag.
- Removed the `asc` alias.
- Refactored CTags configuration.
- Refactored Ruby/RSpec function sections.

# v16.1.0 (2015-07-12)

- Removed extraneous confirmation wording from `gtagd` function.
- Fixed `bashe` alias path to environment settings.
- Updated Git commit message prefix hook to allow fixup! and squash!
- Updated Git remote branch delete functionality.
- Updated `gash` alias as a function with default label support.
- Added Git branch symbol to command prompt.
- Added Git config credential helper for temporary credential caching.
- Added Git stash info to the command prompt.
- Added `bce` alias for `$EDITOR $HOME/.bundle/config`.
- Added `bcim` function for ignoring noisy gem post-install messages.
- Added `besb` alias for `bundle exec rspec spec --seed 2112 --bisect`.
- Added `besf` alias for `bundle exec rspec spec --only-failures`.
- Added `besn` alias for `bundle exec rspec spec --next-failure`.
- Added `bl` alias for `bundle lock`.
- Added `gcs` alias for `git commit --squash`.
- Added `git rerere gc` to `gvac` and `gvaca` functions.
- Added `guke` function (a.k.a. Git Nuke) for permanent file deletion.
- Added `push.followTags = true` to Git config.
- Added interactive error fixing for psql prompt.
- Added missing documentation for private functions.

# v16.0.0 (2015-06-07)

- Removed Git post-receive hook.
- Removed Git post-update hook.
- Removed Git update hook.
- Removed Mackup configuration file.
- Removed experimental Rails templates from the `rew` function.
- Removed nodejs! and iojs! aliases.
- Removed numbered `rew` function options (replaced with strings).
- Fixed Ruby Gems README link.
- Fixed hanging script with invalid option.
- Updated "gbna" function to color non-master branches in red.
- Updated Git hook extension file permissions.
- Updated `hbug` alias to include `--all` option.
- Updated `hbup` alias to include `--all` option.
- Added (enabled) general glob settings to .bashrc.
- Added Git post-applypatch hook.
- Added Git post-merge hook.
- Added Git post-rewrite hook.
- Added `asc` alias for `asciinema`.
- Added `catc` alias for colorized cat.
- Added `rcopa` alias for autogenerating Rubocop configuration.
- Added `rcopo` alias for running single Rubocop cops.
- Added the `gpn` alias for `git push --no-verify`.

# v15.1.0 (2015-03-28)

- Fixed `gash*` functions so that processing emtpy stashes won't error.
- Updated `gbd` function to prompt for local and remote branch deletion.
- Updated `gtail` and `gtaila` functions to sort by unique subject.
- Updated `gup` function message cosmetics.
- Updated `swift` alias to no longer use XCode (beta) path.
- Updated commit message text to focus on questions instead of format.
- Added 'g' option to `dots` function for printing of Git Hooks.
- Added .hushlogin dofile for silencing server welcome messages.
- Added Foreman aliases.
- Added Git hook for Capybara save_and_open_page detection.
- Added Jasmine Git hook support.
- Added Jasmine aliases.
- Added JavaScript to CTag Git hook generation.
- Added RSpec global configuration.
- Added Silver Surfer global configuration.
- Added `gbna` function for listing current branch of all projects.
- Added `gbt` alias for `git show-branch --topics`.
- Added `glg` alias for easy grepping log subject and body.
- Added `ios` alias for launching iOS Simulator.
- Added code of conduct documentation.
- Added default configuration for CTags.
- Added git bisect aliases.
- Added listing and opening of pull requests to `gh` function.
- Added pruning of untracked remote references to `gup` function.
- Added remote fetching of GitHub pull requests to global Git config.
- Refactored Git hook gemfile_path as bundler_gemfile_path.

# v15.0.0 (2015-03-01)

- Removed `gln` alias (use `gld` instead).
- Removed `ggc` alias (use `gvac` instead).
- Removed `gwc` alias (use `gup`, `glame`, `gistory`, etc instead).
- Removed `gashdif` function (use `gashs` instead).
- Removed `hbv` alias as `brew versions` is no longer supported.
- Removed graph and merged commits from `glf` alias output.
- Fixed `gup` function to only display Git activity when there is some.
- Fixed RSpec Git hook to check for `:focus` and `focus:` keys.
- Fixed bug with Git hook long line length detection of commented lines.
- Fixed `gbdm` function so master branch isn't deleted when on a feature branch.
- Fixed `gtail` function so empty output is never copied to clipboard.
- Fixed not returning error statuses for error messages.
- Fixed error with `gashs` function when no stash existed to be shown.
- Updated `gh` documentation (reduced redundant information).
- Updated the Git commit message to use less text.
- Updated `gbs` and `gbd` functions to include branch author and relative date.
- Updated function documentation.
- Updated `glt` alias to sort tags in descending order.
- Updated `glf` alias to list commmits in reverse order.
- Added ability to copy and print commit URL to `gh` function.
- Added ability to print and copy last commit to `gh` function.
- Added `iojs!` and `nodejs!` aliases for toggling between the two.
- Added `key` alias for quickly accessing the OSX Keychain.
- Added `sslc` function for creating SSL certificates.
- Added the `hbsw` alias for `brew switch`.
- Added `hbs` alias for `brew search`.
- Added aliases `hbp` and `hbpu` for `brew pin/unpin` respectively.
- Added `gbdm` function status message when there are no merged branches to delete.
- Added `gtail` error message when using on a non-Git repository.
- Added `gbl` function for listing Git branch information.
- Added usage text when displaying `gashs` options.
- Added Homebrew sbin to PATH.
- Added `pgt` function for editing PostgreSQL template1.

# v14.2.0 (2015-01-11)

- Fixed dotfile searching (i.e. `dots s`) so only function names are returned.
- Fixed dotfile searching (i.e. `dots s`) to allow for full function name searches.
- Fixed `gup` function commit detail output.
- Fixed `gup` function to show git log summary in reverse order.
- Updated `gistory` function to behave like the `gup` function.
- Updated Bash prompt to use 12 hour clock with AM/PM suffix.
- Updated `gifize` function to produce higher quality GIF images.
- Updated `gashs` function to show detailed git stash information.
- Updated `gashs` function to accept git diff/tool options.
- Updated all git stash listings to add commit hash and time ago info.
- Added commit counter for `gup` and `gistory` functions.
- Added formatted section output to `gup` function.
- Added commit history summary to `gistory` function.
- Added aliases for PostgreSQL start/stop.
- Added `pgi` alias for PostgreSQL DB initialization.
- Added PostgreSQL functions for user creation and deletion.
- Added Redis server start and CLI aliases.
- Added `./bin` to .bashrc $PATH setup.
- Added rbenv variables support.
- Added auto-detection of words/phrases to avoid in the Git commit messages.

# v14.1.0 (2015-01-03)

- Updated `gup` function to safely compare previous commit.
- Updated `glamel` function to use full instead of short stats.
- Updated function documentation.
- Added `grm` alias which can reset a merge.
- Added `gcpa` alias for "git cherry-pick --abort".
- Added `gashdif` function for diffing git stashes.
- Added `grom` alias which resets local branch to origin/master.
- Added `gel` alias for "git rm" (a.k.a git delete).
- Added `gelc` alias for ignoring previous tracked file now in .gitignore.
- Added the `gistory` function for reviewing a file's history.

# v14.0.0 (2015-01-01)

- Removed the `geady` alias (use `gri` instead).
- Removed the `gvca` function (use `gvaca` instead).
- Removed .guardrc support.
- Fixed `pss` alias so that grep, itself, is not included in the search.
- Fixed `bessa` output errors with special characters.
- Fixed `gsta` function with not printing special characters.
- Fixed `bua` function so that project update statistics are reliable.
- Fixed .guardrc deprecation warnings related to screen clearing.
- Added `gucca` function for Git upstream commit count.
- Added `rserv` function to serve current directory web content.
- Added `ger` alias for "git rerere".
- Added `dnsf` alias for flushing DNS cache.
- Added `dnss` for printing DNS statistic info.
- Added `gma` alias for `git merge --abort`.
- Added `bashe` alias for editing global bash environment variables.
- Added `rbest` alias for `rails_best_practices`.
- Added 'p' option to `dots` function.
- Added `gri` function for git rebase (interactive).
- Added 'gount' alias which answers total number of project commits.
- Added `gvac` function for Git verify and clean of Git repo objects.
- Added `ginfo` function for "Git Info".
- Added Git pre-commit hook for preventing Gemfile path statements.
- Updated .gitconfig to enable git rerere by default.
- Updated `glast` alias to use `--decorate` option.
- Updated .gitconfig to allow `git status` to show all untracked files.
- Updated `gdw` alias to use colorized word diffs.
- Updated "gash" alias to include untracked files when stashing.
- Updated `gup` function to include summarized git log of fetched changes.

# v13.1.0 (2014-11-02)

- Removed Homebrew aliases for managing services (Homebrew no longer supports these commands).
- Updated JavaScript pre-commit Git hook to check for closing tag in `console.log();` statements.
- Updated JavaScript Git pre-commit hook to check for all console.* statements.
- Updated JavaScript Git pre-commit hooks to exclude minified files.
- Updated Git hook extension function documentation.
- Updated .psqlrc to keep a 1,000 line history.
- Updated .psqlrc to use "\q" instead of CONTROL+D to quit.
- Updated .psqlrc to display query execution times.
- Added the "gup" function for easy reading/diffing of recent Git commits.
- Added Git pre-commit hook for preventing JavaScript `debugger;` statements.
- Added Git pre-commmit hook for detecting JavaScript `alert();` statements.

# v13.0.0 (2014-10-20)

- Removed the "githubi" function.
- Removed the "tfollowers" function.
- Removed the "hpas" alias.
- Removed the "rsite" and "rsitep" aliases.
- Fixed "gia" function so Git hooks are actually initialized for all projects.
- Fixed bug with JavaScript Git hook detecting console.log statements in commented code.
- Fixed bug with Pry Git hook detecting binding.pry or binding.remote_pry statements in commented code.
- Updated Pry Git hook to detect remote debug statements.
- Updated dotfile linking to exclude env.sh, .gemrc, and .gitconfig files from being linked.
- Updated dotfile deletion to exclude env.sh, .gemrc, and .gitconfig files from being deleted.
- Updated options prompt documentation.
- Added Git pre-commit hook for preventing binding.pry statements.
- Added Git pre-commit hook for preventing console.log statements.
- Added Git hook for commit message long line lengths.
- Added "hbc" alias for "homebrew cleanup".
- Added Bash history time format to .bashrc.
- Added GOROOT to $PATH (only if Go is installed).
- Added "bj" function for Bundler job detection/updating.
- Added env.sh for secret/machine-specific environment settings.
- Added "ghd" function for deletion of git hooks for current project.
- Added "ghda" function for deletion of Git hooks for all projects in currenct directory.
- Refactored Bash scripts to .bash folder.
- Refactored home_files with .tt extension.

# v12.2.0 (2014-10-12)

- Fixed "gbdm" function so that only locally merged branches are deleted.
- Fixed dotfile symlinking for nested folder structures.
- Updated "glf" alias to pretty print git log as used by the "gl" alias.
- Updated current directory/git email for bash prompt.
- Updated "glf" alias to always fetch before displaying log.
- Added "gamendh" alias for ammending current changes to HEAD.
- Added "gia" function for initializing/re-initializing all Git repositories in current directory.
- Added Git template directory location to Git repo initialization.
- Added custom Git hooks.
- Added custom Git commit message.
- Added .mackup.cfg home file.

# v12.1.0 (2014-09-29)

- Fixed "gsup" function to only report yesterday's Git log activity.
- Fixed dotfile deletion so symbolic links are included too.
- Updated "gbc" function to always copy new branch name to clipboard.
- Updated Git config to default sort tabs by refname.
- Updated Git config to use full pathnames when using git-grep.
- Updated "gbd" function to display confirmation prompt in red color.
- Updated "gps" and "gpp" aliases to push "stage" and "production" branches respectively.
- Updated dotfile check to include symbolic files.
- Updated dotfiles option prompt descriptions.
- Updated Bash background color codes.
- Updated "gince" function to support optional "--until" filtering.
- Added "gchm" alias for "git checkout master".
- Added "glt" alias which prints git tags with dates.
- Added "bessa" function which runs RSpec and reports results on all projects in current directory.
- Added "gbn" alias which prints and copies current Git branch name to clipboard.
- Added the "gpuro" alias for rebasing upon a remote origin branch.
- Added the "gpurom" alias for rebasing upon the remote orign master branch.
- Added support for installation of nested directories (i.e. those located in the home_files folder).
- Added Bash Powerline prompt support.
- Added Go workspace path.

# v12.0.0 (2014-08-10)

- Removed the 'p' option for "gh" function (replaced with 'r' instead).
- Removed the "rfixes" alias (use "bernf" instead).
- Removed the Rails Engine template option from the "rew" function. Use the
  [Gemsmith](https://github.com/bkuhlmann/gemsmith) gem instead.
- Removed the IRB RA class (replaced as ConsoleKit instead).
- Fixed binding.pry bug with .irb_history file not being resolved correctly in .pryrc settings.
- Fixed bug with Hirb "pager" error when using Pry 0.10.0.
- Fixed bug with not being able to select branches higher than nine in a list.
- Updated .gitignore to exclude .env.sample files.
- Updated 'b' option of "gh" function to accept a 'c' option for opening current GitHub branch in default browser.
- Updated the "gh" function option documentation.
- Added "rcop" alias for running Rubocop with useful defaults.
- Added "pss" alias for easy searching of running processes.
- Added "cdb" alias for "cd -".
- Added "bernt" alias for "ber notes:custom ANNOTATION=TODO".
- Added "bernf" alias for "ber notes:custom ANNOTATION=FIX".
- Added "grc" alias for "git rebase --continue".
- Added "gra" alias for "git rebase --abort".
- Added "gcama" function for making the same commit for all projects in current directory.
- Added 'i' option to "gh" function for opening GitHub project issues.
- Added 'w' option to "gh" function for opening GitHub project wiki.
- Added 's' option to "gh" function for opening GitHub project settings.
- Added 'g' option to "gh" function for opening GitHub project graphs.
- Added 'p' option to "gh" function for opening GitHub project pulse.

# v11.0.0 (2014-06-21)

- Removed the "gres" alias (renamed to "grh" instead).
- Removed the "glamelog" function (renamed to "glamel" instead).
- Added the "gpa" function which will push changes to remote repo for all projects in current directory.
- Added Git config cw: prefix for Charity: Water (removed Gnip).
- Added the "lessi" function for interactive less.
- Added "grs" alias for "git reset --soft HEAD^".
- Added "gbc" function to create and switch to a new local branch.
- Added --set-upstream option to "gpo" alias.
- Added "gcf" alias for "git commit --fixup".
- Added the "gbr" alias for "git branch --move".
- Added "rdbmt" alias for rake db:migrate test.
- Added "gau" alias for "git add --update".
- Added a Tar alias section with support for bzip2 compression/decompression.
- Added "grl" alias for "git reflog".
- Added "grp" alias for "git remote prune origin".
- Added "gbs" function for git branch switching.
- Added line numbers to git grep search (i.e. "gg" alias).
- Added the swift alias for easy access to the Swift console.
- Updated the "gpp" alias and added the "gpr" and "gps" aliases.
- Updated "gps" and "gpp" aliases to use "deploy" branch.
- Updated gitconfig to autosquash rebases by default.
- Updated the "gbd" function to prompt for branch deletion.
- Updated the "beg" alias so that is is a function.
- Updated Bash prompt colors.
- Updated all aliases using "rake" to pass through bundle exec (or binstubs if available) instead.

# v10.0.0 (2014-04-24)

- Removed Espresso files from .gitignore.
- Removed .sass-cache from .gitignore.
- Removed the loading of pry-vterm_aliases within .irbrc.
- Removed --skip-javascript as a default option for the "rew" function.
- Fixed the "boa" function to only check for Gemfile.lock files.
- Updated the "sc", "ss", "sg", and "sdb" functions so they make use of the rails binstub (if it exists).
- Updated the "ber" alias to be a function.
- Updated the "bes" alias to be a function.
- Updated the "bec" alias to be a function.
- Updated the "gpua" function so that project names are always printed.
- Updated the "boa" function to catch for missing gems.
- Updated the "rua" function to indicate Ruby version updates per project.
- Updated the "gunseta" function to only print removed keys.
- Updated the "ggeta" function output for setting keys (found/not found).
- Updated the "gh" function so the 'u' option copies the GitHub URL to clipboard.
- Updated the "guthors" alias to count author commits by name instead of email.
- Added the "bua" function which performs a bundle update for all projets in current directory.
- Added the "tcie" function which can encrypt Travis CI values for projects.
- Added the "bca" function (i.e. bundle clean all) for cleaning up gem build artifacts.
- Added the "sketch" function for converting whiteboard photos into sketch drawnings.
- Added the "ghurn" function which answers the Git commit churn for project files (sorted highest to lowest).
- Added the "glamelog" function which answers the commit history of a specific file.
- Added the "guthorsa" function which answers author commit activity per project (ranked highest to lowest).
- Added the "galla" function for easy adding of all file changes per project.
- Added the "t2s" function which converts a file from tabs to spaces (with optional support for number of spaces).
- Added the "Rails Slim Template (experimental)" option to the "rew" function.
- Added support for GitHub Pull Requests to "gh" function.
- Added environment configs to .gitignore.
- Added code coverage folder to .gitignore.
- Added project information to "gcap" function output.
- Added [Priscilla](https://github.com/Arkham/priscilla) gem support to .irbrc.

# v9.0.0 (2014-02-17)

- Removed the PostgreSQL aliases.
- Updated Gemsmith aliases to use "gs" prefixes.
- Updated the "gtail" function to always copy contents to the clipboard.
- Updated the "gbd" function with descriptive local/remote branch deletion messages.
- Added the "tfollowers" Bash function for capturing and comparing Twitter followers.
- Added Rails Engine default template generation support to the "rew" function.
- Added *.log files to .gitignore.
- Added "gfp" alias for "git fetch --prune".
- Added "gtagd" function for deleting a local and remote tag.
- Added Homebrew aliases.
- Added auto-pagination to "dots" for aliases and functions since they are lengthy.
- Added .psqlrc for an enhanced PostgreSQL prompt.
- Added "port" function for "sudo lsof -i :<port>" to quickly scan file usage on a given port.
- Added "gemp" alias for "gem pristine".
- Added "geme" alias for "gem environment".
- Added "gse" alias for "gemsmith edit".
- Added "gsr" alias for "gemsmith read".
- Added "agf" alias for quick Silver Surfer file searches.
- Refactored the "gashp" alias to be a function with multiple stash prompt support.
- Refactored the "gashs" alias to be a function with multiple stash prompt support.
- Refactored the "gashd" alias to be a function with multiple stash prompt support.
- Refactored the "gashl" alias to a function.

# v8.1.0 (2013-12-03)

- Fixed install requirements to only point to the OSX project.
- Fixed "gls" alias so that search results no longer include graph information.
- Fixed "gsta" function so that Git project status does not display master...origin/master.
- Updated .powconfig to keep Pow alive for three hours instead of one.
- Updated the "gtaila" function to use normal, warning, caution, and danger commit coloring.
- Added the 'v' alias for vim.
- Added .vimrc settings.
- Added .inputrc settings.
- Added "rbil" alias for "rbenv install --list".
- Added "tags" to .gitignore.
- Added Pow HTTPS support.

# v8.0.0 (2013-10-12)

- Fixed "dots" function bug where supplying an option to bypass the options prompt would throw an error.
- Fixed "dots" function so that leading whitespace is properly trimmed from labels and descriptions.
- Fixed function label comments to use "Label:" instead of "Name:" for label definitions.
- Enhanced the "dots" function to be able to print alias and function info grouped by section.
- Enhanced "curli" function by replacing short with long options for readability.
- Enhanced "curli" function to throw an error if URL is not supplied.
- Enhanced "dots" function with the 's' search option for easily searching for an alias/function.
- Enhanced the "rew" function with the [Rails Slim Template](https://github.com/bkuhlmann/rails_slim_template) option.
- Enhanced .gitconfig settings to always auto rebase when pulling down new commits.
- Enhanced .irbrc with the ability to answer HTTP status symbols (as used by Rails).
- Enhanced the "gld" alias format and colors.
- Enhanced bash function documentation with better parameter option documentation.
- Enhanced the "gince" function to throw an error if date/time is not supplied.
- Enhanced the "gince" function to take an optional author parameter.
- Enhanced the "gince" function to use the same formatting as the "gl" and "gld" aliases.
- Enhanced the "gamend" alias to not use the --message option.
- Refactored the "rew" function for readability and maintainability.
- Refactored alias and function code into smaller units of functionality.
- Renamed the following aliases to match existing naming conventions: opf -> pfo, md -> mo
- Renamed the "init_github" function to "githubi".
- Replaced the "gl" alias code with contents of the "gld" alias.
- Split bash functions into private and public function files.
- Switched default visual editor from vi to vim.
- Grouped all of the git log aliases together.
- Added the "curli" function which allows inspection of a remote file, via curl, within default editor.
- Added the "sshe" alias for editing the SSH config of current user within default editor.
- Added the "gh" function for opening GitHub page in default browser for current project.
- Added the RA.http_codes method to IRB (handy when in a Rack app).
- Added the "sv" function which will validate and generator a report for a given site.
- Added the "gdm" and "gdtm" aliases.
- Added the "gdtc" alias for showing a diff of cached/staged changes within difftool.

# v7.0.0 (2013-09-21)

- Fixed function signatures where some functions were missing "()".
- Removed the "gus" alias for "git reset HEAD".
- Added the "gr" alias for "git reset".
- Added "gweek" function which answers Git commit history for the past week.
- Added "gmonth" function which answers Git commit history since beginning of current month.
- Added Kaleidoscope support for diff and merge to gitconfig.
- Added "gdt" alias for launching Git diffs with Kaleidoscope.
- Replaced the "gce" alias with the "gcle" alias for git config local edit of project settings.
- Enhanced the "gcle" alias to use the --edit option for readability.
- Added the "gcge" alias for git config global edit of settings.
- Added the "gaila" function which answers the current email address of all projects in current directory.
- Converted the "gail" alias to a function.
- Dropped the --global option from the "gail" function.
- Added the "gailsa" function which sets the local user email for each project in current directory.
- Added the "gunseta" function which will unset a Git config key for all projects in current directory.
- Added the "dots" function which can print supported alias and function information for all dotfiles.
- Added the "gget" alias for "git config".
- Added the "ggeta" function which answers a value for a given Git config key for all projects in current directory.
- Added the "gseta" function for setting a key=value pair for all projects in current directory.
- Enhanced the "l1" alias to copy output to clipboard.
- Enhanced Pry history to be shared with IRB history.
- Enhanced Pry to default to Sublime Text editor.
- Enhanced Pry debug aliases to be only defined if the Byebug debugger is present.
- Enhanced shell prompt to show dirty and untracked file statuses for git branches.
- Enhanced shell prompt to display Git stash state and upstream differences (if any).
- Enhanced shell prompt to only show current directory and not the full path.
- Enhanced shell prompt to show git branch and committer email address in a blue background.
- Enhanced the dots function to print function name and description information.

# v6.0.0 (2013-08-13)

- Fixed 'l1' alias so that it lists dotfiles (minus . and ..).
- Switched to using sub-shells when traversing sub-directories for all functions.
- Switched from the pry-debugger to pry-byebug gem in irbrc.
- Switched from RDoc to Markdown for documentation.
- Updated the "gall" alias to use the --all option.
- Updated the "gcap" function to use long form Git options for better readability.
- Updated the "rew" function so that flags and local/remote options are easier to understand.
- Updated README to match GitHub project description.
- Updated "rew" local options to point to "Projects" path instead of the "Ruby" path.
- Updated the sc, ss, sg, and sdb functions to support Rails 2.x.x, 3.x.x, and 4.x.x.
- Added the "bertt" function which allows for easier testing of a specific Test::Unit test file.
- Added the "berts" alias for getting a summary of failing (if any) test files (including line numbers).
- Added the "bertv" alias for enabling Test::Unit to run tests in verbose mode.
- Added the "gus" alias (i.e. git reset HEAD).
- Added the "ggc" alias for validating and fixing dangling objects, freeing up disk space, improving performance, etc.
- Added the "gvca" function which validates and cleans all Git projects for current diretory.
- Added the "gail" alias for easily displaying/changing current global email address used for commits.
- Added the "gemuc" alias for gem update and clean of entire system.
- Added the 'w' Pry alias for "whereami".
- Added the "md" alias for opening Markdown files within the Marked app.
- Added a Versioning section to the README.
- Added tsl (list-sessions), tsa (attach-session), tsk (kill-session), and tsr (rename-session) aliases for tmux.
- Added vi as the default visual editor.
- Added the "rua" function for upgrading all projects in current directory to a new ruby version.
- Added Travis CI bash completion support.
- Added missing CHANGELOG, LICENSE, and README files.
- Added NPM to PATH.

# v5.2.0 (2013-05-22)

- Force default Git editor to wait for files to be closed before returning.
- Updated shell script documentation.
- Fixed z.sh warnings when sourcing bashrc.
- Updated bash functions to use read line instead of tweaking the IFS variable for parsing directories with spaces.
- Modified gsta function to display branch status and unpushed changes in addition to uncommitted changes.
- Collapsed while/do statements to a single line.
- Added save to 'gash' alias so that git stashes can optionally be saved with a description.
- Added pretty print formatting to 'gashl' alias for git stash lists.
- Moved git grep (gg) next to git search git log search (gls).
- Dropped the glc alias in favor of the guthors alias (uses the author summary originally provided by the glc alias).

# v5.1.0 (2013-05-11)

- Fixed bug with sublime not being defined prior to loading bash_- files as a necessary dependency.
- Fixed bug with opf alias where paths with spaces would fail to open properly.
- Fixed Git-related Bash functions where directory names would be split with spaces.
- Added the -f option for exporting functions.
- Added ez alias which speeds up opening the ~/.z config in the default editor.
- Added the xrayconfig.txt file which supports the xray-rails gem.
- Added the 'f' alias for the pry-debugger finish command.
- Added pry-rescue support.
- Added Bond gem support to .irbrc and .pryrc.
- Added breakpoint aliases for Pry to .pryrc.
- Added the gdis alias (i.e. git reset --hard).
- Added the gcp alias (i.e. git cherry-pick).
- Added the gpua function which allows one to "git pull" for all git-enable directories in current folder.
- Added boa Bash function which lists outdated gems for each project in current directory.
- Added the gifize function (allows one to easily convert video into an animated GIF.
- Added the gi alias (i.e. git init).
- Refactored the scripts in the functions folder.
- Updated run.sh usage.
- Switched from pry-nav to the pry-debugger gem.
- Updated the gpd Bash function to delete local branch regardless of merge status and made remote branch specific to 'origin'.
- Added gasha function which answers the git stash size of all projects in current directory.
- Renamed instance variable 'directory' to 'project' in directory loops for Bash functions.

# v5.0.0 (2013-04-20)

- Fixed the timeout comment in the pow config.
- Fixed 'Enhancements' spelling typo in irbrc file.
- Default the $EDITOR variable to Sublime Text for all environments.
- Default to 'simple' when pushing (gitconfig).
- Added the gce alias for 'git config -e'
- Added the opf alias (i.e. opens current terminal path as a tab in Path Finder).
- Added Pry aliases for continue, step, and next as c, s, and n.
- Added guardrc support and dropped the -c option from the beg alias (provided via guardrc now).
- Tweaked .pryrc to match Bash prompt settings.
- Added the .aprc file for setting Awesome Print defaults.
- Add the Dotphiles resource to the README.
- Configured Bash history to remove duplicates, keep a history size of 1000, and exclude mundane commands from being entered in history.
- Added Hirb and Awesome Print support to the Pry console.
- Updated the installer to prompt for options before executing.
- Added the install option for checking currently installed file differences.
- Added the install option for linking dotfiles to this project.
- Added the install option for showing available dotfiles for install.
- Added the install option for deleting installed dotfiles.
- Added the geady alias (i.e. git rebase -i @{u}).
- Renamed the 'guthers' alias to 'guthors'.
- Renamed install.sh to run.sh.
- Bumped IRB Eval History to 1000.
- Reduced Bash history size to 1000.

# v4.1.0 (2013-04-14)

- Applied RubyGems 2.0.0 syntax upgrades.
- Added the powconfig file. Thanks Eric.
- Removed the Code Climate badge - Not really relevant for this project.
- Removed the tree alias, using the Tree app instead.
- Added Z support for Bash.
- Added the gba alias (git branch --all).
- Renamed the gpcap alias to gcap and cleaned up the associated documentation.
- Upgraded the gtaila alias to color code counts: 0-9 (white), 10-19 (yellow), 20 or greater (red).
- Fixed if statement in gtaila function color check.
- Cleaned up the gtaila function documentation.
- Added a link to the Dotify project in the README.
- Added purple color to current directory info in shell prompt.
- Added additional Bash color definitions.
- Changed the command prompt colors to the following: timestamp (grey), Git branch (purple), and current directory (cyan).
- Added Nicolas Gallagher's dotfiles to the README.
- Broke up the command prompt code into easier to read segments.
- Switched IRB prompt to match Bash shell prompt (using pipes instead of brackets).
- Added the gls alias (i.e. gl + -S for search).
- Removed Windows support of Thumbs.db in gitignore.txt.
- Removed TextMate support in gitignore.txt.
- Removed SVN support in gitignore.txt.
- Ignore CTag metadata in gitignore.txt.
- Added parameter documentation for init_github function.
- Added the gday function to report git activity across all projects for today only.
- Refactored the duplicate gsup and gday function code into the gince function.

# v4.0.0 (2013-03-17)

- Removed the extra spacing before time in the 'gld' alias.
- Split Bash aliases and functions into separate files.
- Fixed bash prompt so that word wrapping works.
- Fixed diagram aliases to ensure the doc/design folder exists prior to being executed.
- Dropped the debug alias.
- Added cyan coloring for project names in gsta and gsup aliases.
- Added the gcm alias (i.e. git commit -m).
- Added the rbi alias (i.e. rbenv install).
- Cleaned up file permissions.
- Added sgh alias (i.e. script/rails helper).
- Added the gbd alias for deleting local and remote branches.
- Added gbdm alias for deleting all merged branches.
- Added the gtaila function which counts the number of commits from last tag for all projects.
- Moved bash colors into seperate file.
- Removed excess carriage return per project results.
- Added the gpcap alias which commits and pushes changes for all projects that have changes.
- Removed the debundle code.
- Added color comments.
- Added the guthers alias (lists all authers/contributors on a project).
- Added the gap alias (i.e. git add --patch).
- Expanded git alias abbreviations to improve self documentation.
- Expanded all alias abbreviations, where able, in order to be more self documenting.
- Added Adam Jahnke's dotfile project to the README.
- Added the rdd bash alias (i.e. rm -rf _doc).
- Applied Code Climate GPA badge.

# v3.0.0 (2013-01-27)

- Added ipa alias.
- Added the groot alias. Thanks Eoin.
- Added the gwc Git alias.
- Added l1 alias for listing files and directories as single line output only.
- Added a Bash function for reporting Git activity across all projects for standup reports.
- Added Git URL aliases for GitHub and Heroku to gitconfig.txt
- Added the gms alias.
- Added alias for gdc.
- Added the sniff alias for monitoring TCP/IP traffic (pulled from Paul Irish's dotfiles).
- Added the bert aliase for running Test::Unit tests.
- Added the beg alias for running guard.
- Added usage printout for rew function.
- Added third option to rew function which allows for building a new rails project using local rails setup template options.
- Added the glatest git alias which answers the latest update to the project with a datestamp.
- Added the rbu alias (i.e. rbenv uninstall).
- Added support for current git branch to command prompt display.
- Added Bash Completion support.
- Added yellow color to Git branch info in command prompt.
- Added glame alias (i.e. git blame).
- Added the gsta function (i.e. git status all) which answers the status of any project with uncommitted changes.
- Added Code Climate support.
- Added the rbvars alias.
- Added the rfixes alias.
- Added the gtail alias which shows all commits since last tag.
- Added CONTRIBUTING guidelines per GitHub requirements.
- Added Ruby 1.9.x syntax.
- Added the gashl, gashs, gashp, gashd, and gashc for git stash list, show, pop, drop, and clear respectively.
- Modified the command prompt to keep the cursor at the first position.
- Modified the copy to clipboard message for the glh alias.
- Modified the gsup alias to output commits in reverse order (oldest first, newest last).
- Modified the 'ber' alias to be 'bundle exec rake'.
- Modified the rew function to make it easier to select which templates to build from when generating a new Rails app.
- Modified the rew alias so that the template choice can be supplied without always being prompted for one.
- Modified alias rbw to be rbp (i.e. rbenv which) and changed rbw to alias rbenv whence.
- Modified the PRY prompt to resemble the IRB prompt.
- Modified bash prompt colors (grey for time and cyan for git branch info).
- Modified all git logging to show full commit hash.
- Removed the cpath alias and upgraded the p alias to always copy path to clipboard.
- Removed the hard coded author name for the gsup alias - picks up git user name from .gitconfig file instead.
- Removed the Bash color codes.
- Removed Pry editor config since it defaults to sublime.
- Removed the bec alias for cucumber and repurposed it to capistrano (i.e. bundle exec cap).
- Removed the Apache aliases.
- Removed the Ruby GC exports (configured by rbenv-vars - see the OSX project for further details).
- Removed the bers alias and replaced with the bes and bess aliases for using RSpec.
- Removed the Ruby install script and added a Bash script instead.

# v2.2.0 (2012-07-04)

- Fixed awesome_print requirement for .irbrc.
- Removed the .railsrc file and added the "rew" fuction to the .bashrc file with support for multi-template setup.
- Removed the Wirble gem and switched to Wirb.
- Added Pry support (see pryrc.txt).
- Added Ruby heap/memory settings.
- Added rdo alias for quickly launching generated RDoc.
- Added gpur alias for 'git pull --rebase'.
- Added glh alias for acquiring full hash of last commit and auto-copy to clipboard support.
- Added gamend alias for git comment ammending.
- Added glf alias for showing recent git changes in HEAD prior to doing a git pull.
- Added aliases for rbenv.
- Added debundler support the .irbrc file.
- Added IRB auto-completion and history support.
- Added the GitHub Dotfiles project to the README.

# v2.1.0 (2012-04-15)

- Fixed checkout instructions.
- Fixed issues with IRB and Rails IRB command prompts.
- Added sdb alias for rails dbconsole.
- Added RubyMine project files to gitignore file.
- Added Espresso files to gitignore file.
- Added a resource link for bash shell colors.
- Added the rassp and rassc aliases.
- Added Capistrano aliases for stage and production deploys.
- Moved the Rails IRB logic into the irbrc file and left the railsrc file with only default settings.
- Added aliases for Sitemap Generator gem.
- Added alias for bundle outdated.
- Droped RailRoad gem support and switched to the Railroady gem.
- Updated the dmodels, dcontrollers, and dstate aliases.
- Added bcon alias for bundle console.
- Renamed all the gem alises to gem*.
- Dropped TextMate support, switched to Sublime Text 2.
- Changed EDITOR export to point to sublime.
- Changed 's' alias to 'e' to represent the default editor and dropped the dot in the alias.
- Updated the bashs alias with better cross-platform support.
- Replaced use of the tilde with $HOME variable.
- Added OSX and Ubuntu path setup for rbenv.
- Updated README with link to Mathias Bynens' dotfiles project.
- Removed the aliases for clearing rails logs since the rake:log clear tasks does this now.

# v2.0.0 (2012-01-28)

- Fixed the bch and rebundle aliases.
- Added .sass-cache to .gitignore.
- Added rbenv support.
- Added an alias for Heroku+ account switching.
- Added new rails app generation defaults to the .railsrc file.
- Updated the .gitconfig documentation.
- Removed rake call for the 'res' alias.
- Removed the -w option from the Ruby opts export.
- Removed the Icon? option from gitignore.
- Removed the .rmvrc template and RVM support completely.
- Removed the binary warning flag.
- Removed the rdemo and rdemot .bashrc aliases.

# v1.2.0 (2011-12-17)

- Added the glast, gres, and grev Git aliases.
- Removed the ActionView and route configurations from the railsrc.txt file.
- Upgraded to Rails 3.0.11 for Rails Template Setup alias.
- Added Apache start and stop, Gemsmith, and Ruby profile aliases.
- Added git stash alias.
- Added the additional aliases for bundler: b, bch, bi, bu, and be.
- Added references to James Edward Grey II and Gabe Berke-Williams' dotfiles projects.
- Added project-specific default settings for RVM.
- Updated the IRB copy to clipboard method and added a paste method.
- Added bolded and underlined colors as well as background colors.
- Added link for Bash colors.
- Added the gln alias for git log --name-status.
- Added the init_github method to the bashrc file.
- Renamed setup.rb to install.rb and added configuration documentation to the README.
- Added the gemrc.txt template.
- Added RVM fix for loading new Ruby environments when creating new terminal tabs.
- Updated README with new Gemsmith specs.

# v1.1.0 (2011-07-19)

- Removed FileUtils requirement for setup.rb.
- Added existing file check with corresponding console notification.

# v1.0.0 (2011-07-16)

- Initial version.
