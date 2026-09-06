# Mentor OS 官方二进制分发

源码仓库私有，本仓只放安装包。当前版本 v0.9.20：

-  — Windows 10/11 x64（289MB，NSIS，未签名：SmartScreen 选「更多信息 → 仍要运行」）
-  — macOS 12+ Apple Silicon（Intel Mac 暂未出包）

用户机零 Python/Node 依赖。首启自动创建全新数据目录；内存 ≥16GB 的机器会后台从 ModelScope（国内直连）下载完整向量模型，重启后语义检索自动升级到生产同级 bge-m3。

问题反馈：Gitee issue → https://gitee.com/zhao-zihao-zero/mentor-os/issues
