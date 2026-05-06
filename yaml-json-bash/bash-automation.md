# Bash Automation

## Overview
Bash automation is about reliable scripts that can run in CI.

## Key ideas
- Make scripts idempotent (safe to run many times)
- Log what the script is doing

## Example
```bash
#!/bin/bash
set -e
mkdir -p logs
cp app.log logs/app.log
```

## Interview questions
- What does idempotent mean?
- How do you make scripts safer?
