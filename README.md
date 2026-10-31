# 智能分段插件 (Smart Segmentation Plugin)

[![Release](https://img.shields.io/github/v/release/Wenaixi/mai-smart-typing-segment?style=flat-square&color=blue&label=release)](https://github.com/Wenaixi/mai-smart-typing-segment/releases)
[![CI](https://img.shields.io/github/actions/workflow/status/Wenaixi/mai-smart-typing-segment/ci.yml?branch=main&style=flat-square&label=CI)](https://github.com/Wenaixi/mai-smart-typing-segment/actions)
[![License](https://img.shields.io/badge/license-GPL--v3.0--or--later-green?style=flat-square)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.12%20%7C%203.13-blue?style=flat-square)](https://www.python.org/)
[![MaiBot](https://img.shields.io/badge/MaiBot-1.2%2B-orange?style=flat-square)](https://docs.mai-mai.org)

> 本插件由 [Wenaixi](https://github.com/Wenaixi) 维护，是专为生产环境深度调优的高可用分支。

## 简介与定位

使用 LLM 将长文本在最自然的语义断句处切分成短句分开发送，还原真人打字感。

- **插件目录**：`wenaixi_mai_smart_typing_segment`
- **开源许可证**：`MIT`

---

## 核心特性与本地深度调优

- 根据主人指令调优为 min_length = 3，短句长句全量享受智能分段体验

---

## 指令与工具速查

### 常用指令 (Command)
- `/smart_seg - 查看或开关智能分段状态`

### 大模型工具 (Tool)
- `(出站消息切分处理，无独立工具)`

---

## 快速配置

配置文件统一定位于插件根目录下的 `config.toml`。修改后重启或通过 WebUI 热重载即可生效。

---

## 上游项目与开源溯源

- **原作者 / 组织**：`saberlights`
- **官方原版开源仓库**：[https://github.com/saberlights/smart_segmentation_plugin](https://github.com/saberlights/smart_segmentation_plugin)
- **开源协议**：`MIT`
- **声明**：本项目遵循开源协议，特此致敬原作者的杰出贡献。本分支针对生产环境的高并发网络、个性化社交和抗风控需求进行了深度稳定性修复与定制化演进。