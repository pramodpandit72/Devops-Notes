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
- `$?` last command exit code
- `set -e` exit on error
- `set -u` error on unset variables
- `set -o pipefail` fail on pipeline errors

## Interview questions
- What does `set -e` do?
- How do you handle errors in a script?
