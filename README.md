# git-hooks
Repository of proper git hooks.

# Summary
There are a number of git hook examples on the internet that don't take the examples and manual into approach. This repository attempts to not increment that number.

# Hooks

## pre-commit

The pre-commit hook uses the the `remote ref` passed into it through standard input to disallow pushing to a certain remote branch.
