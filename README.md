
## 1. When does Git perform a fast-forward and when is a merge commit created?
Git performs a fast-forward when the branch being merged has all commits ahead of the target branch, and creates a merge commit when the target branch has independent commits.

## 2. What is the practical difference between merge and rebase?
Merge preserves branch history and may create a merge commit, while rebase rewrites commits on top of another branch to create a linear history.

## 3. How was the conflict resolved in your repository?
The conflict in Program.cs was resolved by deliberately choosing the main branch version for the `number` variable.
