# Linux Commands

## Overview
Daily work depends on a small set of reliable commands.

## Common commands
- `touch file` use: create an empty file
- `head -n 10 file` use: show the first 10 lines
- `tail -n 10 file` use: show the last 10 lines
- `grep -n "text" file` use: search text with line numbers
- `find /path -name "*.log"` use: find files by name
- `ps aux` use: list running processes
- `top` use: live process view
- `kill -9 PID` use: force stop a process
- `df -h` use: show disk usage
- `du -sh folder` use: show folder size

## Interview questions with answers
- Q: How do you find a file by name?
	A: Use `find /path -name "name"`.
- Q: How do you see disk usage?
	A: Use `df -h` for disks and `du -sh folder` for a folder.
- Q: How do you stop a running process?
	A: Find the PID with `ps aux` and stop it with `kill`.
