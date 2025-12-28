# XV6-based-on-xuanwu-

本仓库为基于 xuanwu 版本的 XV6 教学/实验系统的镜像与源码导入。包含内核源码、用户态程序、构建脚本和测试用例。

来源说明
- 本仓库基于原始 xv6-riscv 项目导入并做了重新初始化提交，历史已重置为单次导入提交。

快速开始（在 Linux 环境）

1. 安装 RISC-V 工具链（示例）

```bash
# 示例：Ubuntu 下安装 riscv 工具链（请根据实际需要调整）
sudo apt-get install gcc make pkg-config qemu-system-misc
# 如果需要交叉编译器，请安装 riscv64-unknown-elf 工具链
```

2. 在仓库根目录构建并运行（常见命令）

```bash
make        # 构建 xv6
make qemu   # 使用 QEMU 运行（如 Makefile 支持）
```

更多信息请参考仓库内 `Makefile` 与 `README` 中的具体说明。

如果需要我帮你添加 CI 或其他自动化脚本，请告诉我你的需求。
