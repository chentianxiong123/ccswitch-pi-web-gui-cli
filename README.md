# CC-Switch Pi Fork — 三合一归档仓库

本仓库将 CC-Switch 的 Pi agent 定制三部分合并归档，结构如下：

```
/
├── README.md      # 本文件
├── web/           # Web 运行时（默认分支，官方交付物形态）
├── cli/           # CLI 形态
└── gui/           # GUI 形态
```

## 内容说明

| 目录 | 说明 | 提交数 |
|---|---|---|
| `web/` | Web 运行时（Vue + Rust），Pi agent 支持完整版 | 56 |
| `cli/` | CLI 形态，ARM32/armv7 构建支持 | 13 |
| `gui/` | GUI 形态（Tauri），独立来源 | 12 |

## 来源

本仓库为 `farion1231/cc-switch` 的 fork，针对 Pi (pi-agent) 做了定制。
三个目录分别对应 fork 时的三个独立分支（web / cli / gui），合并到默认分支 `web` 归档。

## 说明

- 默认分支：`web`
- 各目录的完整提交历史均已并入默认分支历史，贡献统计保留
