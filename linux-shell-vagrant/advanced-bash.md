# Advanced Bash

## Overview
Advanced Bash improves automation and reliability.

## Key ideas
- Use functions and loops
- Check exit codes
- Use `set -e` to stop on errors

## Examples
```bash
set -e
for f in *.log; do
  echo "Processing $f"
  grep -n "ERROR" "$f" || true
done
```

## Important commands
- `$?` use: read the last command exit code
- `set -e` use: exit on error
- `set -u` use: fail on unset variables
- `set -o pipefail` use: fail a pipeline if any command fails

## Interview questions with answers
- Q: What does `set -e` do?
  A: It stops the script when a command fails.
- Q: How do you handle errors in a script?
  A: Check exit codes and use `set -e` plus clear logging.
