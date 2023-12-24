# 安装 docker，docker-compose

 - 将所有文件上传服务器
 - 切换服务器root权限
 - 修改 install.sh 权限，命令：chmod +x install.sh
 - 执行 ./install.sh 即可

## 离线包下载
 - docker: https://download.docker.com/linux/static/stable/x86_64/
 - docker-compose: https://github.com/docker/compose/releases
## 命令补全

### docker 命令补全
 - centos:  yum install -y bash-completion && source /usr/share/bash-completion/bash_completion
 - ubuntu: apt-get install -y bash-completion && source /usr/share/bash-completion/bash_completion

### docker-compose 命令补全
 - curl -L https://raw.githubusercontent.com/docker/compose/$(docker-compose version --short)/contrib/completion/bash/docker-compose > /etc/bash_completion.d/docker-compose



alias ip='curl ip.sb'
alias bypy='python -m bypy'
source  /root/z/z.sh
alias mk='function __mkcd(){ if [ $# == 1 ]; then mkdir $1; cd $1; unset -f __mkcd; elif [ $# == 2 ]; then mkdir $1 $2; cd $2; unset -f
__mkcd; fi }; __mkcd'
alias gc='git clone'
cd /root/dockerdata
alias yd='sh /root/dockerdata/jellyfin/download_bili_video.sh'
alias yt='yt-dlp'
alias dc='docker-compose'
alias di='docker images'
alias dp='docker ps -a'
alias de='docker exec -it'
alias dk='docker'
alias rm='rm -i'
alias cp='cp -i'
alias mv='mv -i'
alias ls='ls -l'
alias dl='docker logs'
alias dy='nano docker-compose.yml'
alias dri='docker rmi '
alias ds='docker stop '
alias dup='docker-compose up -d '
alias dcd='docker-compose down'
alias drf='docker rm -f '
alias cdd='cd /root/dockerdata'












