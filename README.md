# commit-hooks

This repo contains pre-commit hooks I use to make running git operations smoother. 

Currently, this repo contains the following commit hooks:
- prepend-branch-name (prepends the branch name followed by ':' to the commit msg, useful for linking Jira tickets with commits)

## Usage
From within this directory, run the following command to add this repo's contents to the set of global commit hooks.

```
$> git config --global core.hooksPath $(pwd)
$> chmod u+x $(pwd)/**/*.sh
```

## Additional References
- https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks
- https://github.com/aitemr/awesome-git-hooks