# Commands Index

All important commands grouped by topic.

## Linux basics
- `pwd` use: show current directory
- `ls -la` use: list files with details
- `cd /path` use: change directory
- `mkdir name` use: create a folder
- `rm -rf name` use: remove a file or folder
- `cp src dst` use: copy files or folders
- `mv src dst` use: move or rename files
- `cat file` use: show file content
- `less file` use: view file content page by page

## Linux commands
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

## File permissions
- `ls -l` use: view permissions
- `chmod 644 file` use: set permissions
- `chmod +x script.sh` use: make a script executable
- `chown user:group file` use: change owner and group

## Shell scripting
- `bash script.sh` use: run a script
- `chmod +x script.sh` use: make it executable
- `./script.sh` use: run it directly

## Advanced bash
- `$?` use: last command exit code
- `set -e` use: exit on error
- `set -u` use: fail on unset variables
- `set -o pipefail` use: fail pipelines on errors

## Vagrant
- `vagrant init` use: create a Vagrantfile
- `vagrant up` use: start the VM
- `vagrant ssh` use: connect to the VM
- `vagrant halt` use: stop the VM
- `vagrant destroy` use: remove the VM

## JSON tools
- `jq '.' file.json` use: pretty print JSON
- `jq '.name' file.json` use: read a field

## Git
- `git init` use: start a repo
- `git status` use: show status
- `git add .` use: stage changes
- `git commit -m "msg"` use: commit changes
- `git log --oneline` use: view history
- `git diff` use: show changes
- `git branch` use: list branches
- `git branch feature` use: create a branch
- `git checkout feature` use: switch branch
- `git switch -c feature` use: create and switch
- `git merge feature` use: merge branches

## AWS
- `ssh -i key.pem user@ip` use: connect to EC2
- `aws s3 ls` use: list buckets
- `aws s3 cp file s3://bucket/` use: upload a file

## Docker
- `docker build -t app .` use: build an image
- `docker run -p 8080:80 app` use: run a container
- `docker ps` use: list running containers
- `docker images` use: list images
- `docker logs <id>` use: view logs
- `docker compose up -d` use: start services
- `docker compose down` use: stop services
- `docker network ls` use: list networks
- `docker network create mynet` use: create a network
- `docker network inspect mynet` use: inspect a network

## Maven
- `mvn -v` use: show Maven version
- `mvn clean` use: remove build output
- `mvn test` use: run tests
- `mvn package` use: build an artifact

## Jenkins
- `Jenkinsfile` use: pipeline as code (file)

## CI/CD
- `.github/workflows/*.yml` use: GitHub Actions workflows
- `.gitlab-ci.yml` use: GitLab CI pipeline

## Ansible
- `ansible --version` use: show Ansible version
- `ansible all -m ping -i hosts` use: test connectivity

## Kubernetes
- `kubectl get nodes` use: list nodes
- `kubectl get pods` use: list pods
- `kubectl apply -f file.yaml` use: apply a manifest
- `kubectl get deploy` use: list deployments
- `kubectl rollout status deploy/name` use: check rollout status
- `kubectl rollout undo deploy/name` use: roll back a deployment
- `kubectl get svc` use: list services

## Projects
- `docker build -t myapp .` use: build the app image
- `docker run -p 8080:8080 myapp` use: run the container
- `kubectl apply -f deployment.yaml` use: create or update a deployment
- `kubectl apply -f service.yaml` use: create or update a service
