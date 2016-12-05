# Git Essentials

- November 3-4, 2016
- Facilitators:
  - Briana Swift (@brianamarie)

## Resources

- [git-scm](https://git-scm.com)
 
## Scripts for Adding Files

- **Bash:** `for d in {1..6}; do touch file$d.md; git add file$d.md; git commit -m "adding file $d"; done`
- **PowerShell:** `for ($d=1; $d -le 6;$d++) { touch file$d.md; git add file$d.md; git commit -m "adding file$d.md";}`

## Playgrounds for practicing branching
- [LearnGitBranching](http://learngitbranching.js.org/?NODEMO)
- [GitSchool - Visualizing Git](http://git-school.github.io/visualizing-git/)
