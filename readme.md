# Docker Git Diff
A small docker command that takes three arguments

1. Repo URL (with login if needed)
2. From sha
3. To sha

The command will then run `git dif --compact-summary` on the repository