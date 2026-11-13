# Termux-aarch64-pd-ProotDistro  
Termux虚拟化系统(aarch64 架构)本地tar.xz  
旨在解决“proot-distro install”指令拉取网络包时坏源的情况  

安装命令：   
proot-distro install -n [容器名字]  [本地tgz路径/链接]  
示例：  
proot-distro install -n myubuntu ~/ubuntu-questing-aarch64-pd-v4.37.0.tar.xz  
proot-distro install -n myalpine https://github.com/Ls-WanMeng/Termux-aarch64-pd-ProotDistro/releases/download/20261113/alpine-aarch64-pd-v3.24.4.tgz
