CHECK
=====

Simple time tracking software using bash and git.

Clone this repository, create an alias/symlink to ``check``, and use like this:

```bash
# Show current period (curren.txt)
check

# Check in. Appends checkin time to current.txt and creates a commit.
check in

# Check out. Appends checkout time to current.txt and creates a commit.
check out

# Appends current.txt to a file named after the current date and empties it.
check rotate

# List periods (files)
check list

# Check specific period
check show [file]

# Calculate number of hours in a period
check sum [file]

# Convinience method to run git commands like "check git push".
check git ...
```
