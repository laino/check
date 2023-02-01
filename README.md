CHECK
=====

Simple time tracking software using bash and git.

Clone this repository, create an alias/symlink to ``check``, and use like this:

```bash
# Check current period
check

# Check in. Appends checkout time to current.txt and creates a commit.
check in

# Check out. Appends checkout time to current.txt and creates a commit.
check out

# Appends current.txt to a file named after the current date and empties it.
check rotate

# Convinience method to run git commands like "check git push".
check git ...
```
