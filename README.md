# gitfetch
A way of quickly and easily accessing information on a local git repository using the command line.

## Usaage
`gitfetch` is a command line utilise and therefore is called using the command. An example of calling gitfetch with the expected output is provided below.
```
$ gitfetch

repo.name@user.name
-------------------
Commits: commits.count
Commits by you: commits.count.by.name (percentage)
Branches: branches.count
Contributers: contributers.count
Files: file.count (% code files)
Directories: dir.count
Code lines: number of code lines (estimate)
Upstream: github/gitlab upstream user/repo.name
Languages: 
 - Go     ---------------------------------- (%lines, %files)
 - Rust   --------------                     (%lines, %files)
 - Python ------                             (%lines, %files)
 - Bash   --                                 (%lines, %files)
```


