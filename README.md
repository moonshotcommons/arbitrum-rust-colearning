# Arbitrum Rust 共学营

欢迎来到 Arbitrum Rust 共学营！本仓库用于收集学员的作业提交。

## 📁 文件夹命名规范

请创建以下格式的个人文件夹：

```
submissions/arbitrum-rust-colearning-xxx
```

其中 `xxx` 为你的 GitHub 用户名。

例如：`arbitrum-rust-colearning-alice`

---

## 📂 提交结构示例

具体任务请参照 task 目录下的 README.md 文件, 提交结构如下:

```
arbitrum-rust-colearning/
├── task1/
│   └── README.md                   # 任务说明
├── arbitrum-rust-colearning-alice/
│   └── task1/
│       ├── README.md               # 📝 包含所有5个关卡的运行结果截图
│       ├── level1-connect-testnet/
│       │   ├── Cargo.toml
│       │   └── src/
│       │       └── main.rs
│       ├── level2-query-balance/
│       │   ├── Cargo.toml
│       │   └── src/
│       │       └── main.rs
│       ├── level3-gas-calculator/
│       │   ├── Cargo.toml
│       │   └── src/
│       │       └── main.rs
│       ├── ...
└── arbitrum-rust-colearning-bob/
    └── task1/
        └── ...
```

## 🚀 开始学习

1. **Fork 本仓库**
2. **创建你的个人文件夹**（按照命名规范）
3. **完成各关卡任务**
4. **提交 Pull Request**

## 📚 相关资源

- [ethers-rs 文档](https://docs.rs/ethers/latest/ethers/)
- [Arbitrum 开发文档](https://docs.arbitrum.io/)
- [Arbitrum 测试网浏览器](https://sepolia.arbiscan.io/)

## 💡 提示

- 确保所有代码都能成功编译运行
- **所有关卡的运行结果截图统一放在 `task/README.md` 中展示**
- 注意保护私钥安全，不要将私钥提交到代码库
