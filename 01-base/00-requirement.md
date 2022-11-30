# 硬件要求
您可以在 VPS (虚拟服务器) 或 独立服务器上进行安装 TBS 系统, 以下是详细的配置要求

| 硬件 | 最低配置           | 推荐配置           |
| ---- | ------------------ | ------------------ |
| CPU  | 单核               | 四核               |
| 内存 | 1GB                | 8GB                |
| 硬盘 | 10G 可用空间       | 50G 可用空间       |
| 网络 | 有良好的互联网连接 | 有良好的互联网连接 |



## 操作系统基础要求

-  Linux 内核版本高于或等于 3.10
-  64 位操作系统
-  aarch / x86_64 系统架构 (可通过命令 `uname -m` 查看)
-  支持 Docker 安装

### 兼容性测试

:::tip

我们推荐使用 [Ubuntu](https://releases.ubuntu.com/) / [Debian](https://cdimage.debian.org/cdimage/unofficial/non-free/cd-including-firmware/current/amd64/iso-cd/) 操作系统, 这些发行版支持直接升级操作系统而不需要重装

:::

|                  | 操作系统名称    | 备注                        |
| ---------------- | --------------- | --------------------------- |
| ❌ 可用, 但不推荐 | CentOS 7        | 已停止维护 & 软件版本不兼容 |
| ❌ 可用, 但不推荐 | CentOS 8        | 已停止维护                  |
| ❌ 可用, 但不推荐 | CentOS 8 Stream | 已停止维护                  |
| ✅ 兼容           | CentOS 9 Stream |                             |
| ✅ 兼容           | AlmaLinux 8     |                             |
| ✅ 兼容           | AlmaLinux 9     |                             |
| ✅ 兼容           | RockyLinux 8    |                             |
| ✅ 兼容           | RockyLinux 9    |                             |
| ✅ 兼容           | Ubuntu 18       |                             |
| ✅ 兼容           | Ubuntu 20       |                             |
| ✅ 兼容           | Ubuntu 22       |                             |
| ✅ 兼容           | Debian 9        |                             |
| ✅ 兼容           | Debian 10       |                             |
| ✅ 兼容           | Debian 11       |                             |

:::caution

Windows / macOS 的支持可通过安装 Docker Desktop 来支持, 该部分我们没有完全测试过

:::