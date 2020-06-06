# docker-git-alpine-arm64
Based on https://github.com/alpine-docker/git/blob/master/Dockerfile

Example usage:
```
alias git="docker run --rm -it -v $(HOME):/root -v $(pwd):/git ortinnen/docker-git-alpine-arm64"
git clone https://github.com/Ortinnen/docker-git-alpine-arm64.git
```
