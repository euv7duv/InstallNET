# InstallNET

VPS 一键重装系统脚本（MoeClub InstallNET 镜像，原版未修改）。

## 一键使用

```bash
bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/euv7duv/InstallNET/main/InstallNET.sh') -u 20.04 -v 64 -p <你的密码>
```

参数说明：

- `-u 20.04`：安装 Ubuntu 20.04
- `-v 64`：64 位
- `-p <你的密码>`：设置 root 密码（请替换为你自己的密码）

更多参数（Debian / CentOS、自定义镜像等）请直接看 `InstallNET.sh` 源码注释。
