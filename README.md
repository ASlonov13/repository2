# repository2
capybara

#Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test
$ git config --global user.name Inky                                              git config --global user.email kardanov0709@gmail.com                           git config --global core.autocrlf true                                          git config --global core.safecrlf true
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    --worktree            use per-worktree config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-pattern]
    --get-all             get all values: key [value-pattern]
    --get-regexp          get values for regexp: name-regex [value-pattern]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value-pattern]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-pattern]
    --unset-all           remove all matches: name [value-pattern]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    --fixed-value         use string equality when comparing values to 'value-pattern'
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <type>     value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)
    --show-scope          show scope of config (worktree, local, global, system, command)
    --default <value>     with --get, use default value when missing entry


Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test
$ git clone https://github.com/ASlonov13/repository2
Cloning into 'repository2'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test
$ cd repository2

Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test/repository2 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test/repository2 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test/repository2 (main)
$ git add .
g
Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test/repository2 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test/repository2 (main)
$ git commit -m "first commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Inky@DESKTOP-QRDGB0B.(none)')

Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test/repository2 (main)
$ --global
bash: --global: command not found

Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test/repository2 (main)
$ git config --global user.name Akhmed

Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test/repository2 (main)
$ git commit -m "first commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Inky@DESKTOP-QRDGB0B.(none)')

Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test/repository2 (main)
$   git config --global user.email "ordlomt@gmail.com"

Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test/repository2 (main)
$

Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test/repository2 (main)
$  git config --global user.name "Akhmed"

Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test/repository2 (main)
$ git commit -m "first commit"
[main aff2ce4] first commit
 1 file changed, 2 insertions(+), 1 deletion(-)

Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test/repository2 (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 260 bytes | 130.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/ASlonov13/repository2
   8cc4e32..aff2ce4  main -> main

Inky@DESKTOP-QRDGB0B MINGW64 ~/Desktop/Git test/repository2 (main)
$
