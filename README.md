# Linux-Commands
A custom list of utility commands in Linux system.

#### Find and Replace in Multiple Files
`grep -rl "old_string" . | xargs sed -i 's/old_string/new_string/g'`

Recursively replaces old_string to new_string in all files.
