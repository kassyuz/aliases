# aliases

Alias to list host and port of running process

``` bash
alias listen="lsof -iTCP -sTCP:LISTEN -P"
alias listen="lsof -iTCP -sTCP:LISTEN -P"
alias gpl="ggpull"
alias k8s="kubectl config use-context"
alias gs="git status"
alias k="kubectl"
alias gfast="gaa && git commit --amend --no-edit && ggpush -f "
alias dlb="git branch | grep -v '^*' | xargs git branch -d "
alias podsnr="kubectl get pods --all-namespaces|grep 0/|grep -v Evicted|grep -v Completed "
