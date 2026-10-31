# CLAUDE.md - 智能分段插件 (Smart Segmentation Plugin) (saberlights_smart-segmentation-plugin)

## 1. 模块定位与系统职责
- **插件标识符**：`saberlights_smart-segmentation-plugin`
- **当前生效版本**：`v1.1.0`
- **托管仓库**：[`Wenaixi/smart_segmentation_plugin`](https://github.com/Wenaixi/smart_segmentation_plugin)
- **核心定位**：使用 LLM 将长文本在最自然的语义断句处切分成短句分开发送，还原真人打字感。

## 2. 关键工程规范与配置说明
- **配置路径**：`config.toml`（所有业务调优与鉴权参数收敛于此）；
- **数据持久化**：优先遵循 MaiBot SDK 标准持久化规范，不直接向源码目录写入易失数据；
- **编码与日志规范**：严格遵循 PEP 8 风格，文档与代码注释杜绝 emoji，避免虚假套话。

## 3. 本地深度定制与稳定性修复
根据主人指令调优为 min_length = 3，短句长句全量享受智能分段体验。

---

## 上游项目与开源溯源
- **原作者 / 组织**：`saberlights`
- **官方上游仓库**：[https://github.com/saberlights/smart_segmentation_plugin](https://github.com/saberlights/smart_segmentation_plugin)
- **开源许可证**：`MIT`
- **分支演进模式**：本仓库作为主人的深度定制与生产维护分支（`Wenaixi/smart_segmentation_plugin`）。在保持与官方上游架构演进对齐的同时，锁死并持续维护针对本服务器生产环境的稳定性补丁与核心特性。
