## 前置安装项
1. 安装git。 检查是否系统已经安装了git, 使用命令: `git - -version`, 如果没有安装，see [git下载安装指南](https://git-scm.com/downloads)。
2. 安装docker CommunityEdition, 从根据你的操作系统以下链接查看下载安装指南：
   * [Mac (macOS)](https://docs.docker.com/docker-for-mac/install/)
   * [Microsoft Windows 10](https://docs.docker.com/docker-for-windows/install/)
   * Linux:
      + [CentOS](https://docs.docker.com/install/linux/docker-ce/centos/)
      + [Debian](https://docs.docker.com/install/linux/docker-ce/debian/)
      + [Fedora](https://docs.docker.com/install/linux/docker-ce/fedora/)
      + [Ubuntu](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
  安装前可能需要注册docker账号。如果仍有问题，see [docker 安装指南](https://docs.docker.com/install/)
3. 安装docker-compose, 如果你的系统是Mac or Windows， docker-compose已经一并安装了。请用`docker-compose --version`命令确认。  
对于linux系统, 执行以下两条命令:
```bash
sudo curl -L "https://github.com/docker/compose/releases/download/1.24.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

sudo chmod +x /usr/local/bin/docker-compose
```
如果仍有有问题，请检查dependency packages，see [docker-compose 安装指南](https://docs.docker.com/compose/install/)中linux的tab. 