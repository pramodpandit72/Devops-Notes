# File Permissions

## Overview
Permissions decide who can read, write, or execute a file.

## Key ideas
- Three roles: user, group, others
- Three permissions: read (r), write (w), execute (x)

## Important commands
- `ls -l` view permissions
- `chmod 644 file` set permissions
- `chmod +x script.sh` make a script executable
- `chown user:group file` change owner

## Example
- `-rw-r--r--` means: user can read/write, group can read, others can read.

## Interview questions
- What does `chmod 755` mean?
- Why is execute permission important for scripts?
