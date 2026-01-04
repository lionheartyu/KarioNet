# KairoNet

KairoNet 是一个基于 C++ 的高性能网络库，灵感来源于 Muduo 网络库，并在其基础上进行了重构和优化。该项目旨在为开发者提供一个高效、易用、可扩展的网络编程框架，适用于高并发服务器开发、网络应用原型设计等多种场景。

## 特性

- **高性能**：采用多线程和事件驱动模型，充分利用多核 CPU 性能。
- **易用性**：简洁的 API 设计，便于快速上手和集成。
- **可扩展性**：模块化设计，方便功能扩展和定制。
- **跨平台**：支持主流 Linux 发行版，易于部署。

## 快速开始

### 1. 克隆项目

```bash
git clone https://github.com/yourusername/KairoNet.git
cd KairoNet
```

### 2. 赋予构建脚本执行权限

在项目根目录下运行：

```bash
chmod +x autobuild.sh
```

### 3. 编译项目

运行自动构建脚本：

```bash
./autobuild.sh
```

或手动使用 `make` 进行编译：

```bash
make
```

### 4. 运行示例程序

1. 进入 `example` 目录：

    ```bash
    cd example
    ```

2. 根据实际网络环境，**修改测试文件中的 IP 地址**（如 `example_server.cpp` 或 `example_client.cpp`）。

3. 编译并运行示例：

    ```bash
    make
    ./example_server   # 或 ./example_client
    ```

## 测试

项目自带单元测试，位于 `tests` 目录。你可以通过以下命令运行测试：

```bash
cd tests
make
./run_tests
```

## 贡献

欢迎提交 Issue 和 Pull Request！如有建议或发现问题，请在 GitHub 上反馈。

如需更多帮助，请查阅项目文档或联系维护者。