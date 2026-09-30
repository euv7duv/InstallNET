# InstallNET

VPS 一键重装系统脚本镜像（均为原版，未修改）。

## reinstall.sh（推荐，支持 Ubuntu 24.04）

来源：bin456789/reinstall

```bash
bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/euv7duv/InstallNET/main/reinstall.sh') ubuntu 24.04 --password '你的密码'
```

- 支持 Ubuntu 18.04 / 20.04 / 22.04 / **24.04** / 26.04，以及 Debian、Alpine 等
- `--password` 传 root 密码（请替换为你自己的密码，不要写进任何文件）
- 完整参数说明见上游仓库：https://github.com/bin456789/reinstall

## InstallNET.sh（经典版，最高 Ubuntu 20.04）

来源：MoeClub

```bash
bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/euv7duv/InstallNET/main/InstallNET.sh') -u 20.04 -v 64 -p <你的密码>
```

参数说明：

- `-u 20.04`：安装 Ubuntu 20.04
- `-v 64`：64 位
- `-p <你的密码>`：设置 root 密码（请替换为你自己的密码）

注意：此脚本 Ubuntu 版本映射最高只到 20.04，要装 24.04 请用上面的 reinstall.sh。
