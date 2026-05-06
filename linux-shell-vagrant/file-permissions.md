# File Permissions

## Overview
Permissions decide who can read, write, or execute a file.

## Key ideas
- Three roles: user, group, others
- Three permissions: read (r), write (w), execute (x)

## Important commands
- `ls -l` use: view permissions on files
- `chmod 644 file` use: set permissions (rw-r--r--)
- `chmod +x script.sh` use: make a script executable
- `chown user:group file` use: change file owner and group

## Example
- `-rw-r--r--` means: user can read/write, group can read, others can read.

## Interview questions with answers
- Q: What does `chmod 755` mean?
	A: Owner can read/write/execute, group and others can read/execute.
- Q: Why is execute permission important for scripts?
	A: Without it, the OS will not allow running the script directly.
