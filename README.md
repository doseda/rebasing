# Git rebase
* change base: `git rebase <branch>`
* change base and fixup commits: `git rebase -i <branch>`
* change base and fixup commits automatically:
    * `git commit --fixup=HEAD`
    * `git rebase -i --autosquash develop`
* `git push -f` vs `git push --force-with-lease`
