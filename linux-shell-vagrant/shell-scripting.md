# Shell Scripting

## Overview
Shell scripts automate repeated tasks.

## Key ideas
- Scripts are plain text files.
- Start with a shebang: `#!/bin/bash`

## Basic example
```bash
#!/bin/bash
NAME="DevOps"
echo "Hello $NAME"
```

## Important commands
- `bash script.sh` use: run a script with bash
- `chmod +x script.sh` use: make it executable
- `./script.sh` use: run it directly

## Interview questions with answers
- Q: What is a shebang?
	A: The first line like `#!/bin/bash` that tells the OS which interpreter to use.
- Q: How do you pass arguments to a script?
	A: Add them after the script name and read them with `$1`, `$2`, etc.
