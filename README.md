# ML Skill - ML模型训练协作Skill

一个完整的深度学习训练工作流协作skill，通过8个专业subagent协作完成从项目启动到模型部署的全流程。

## 概述

本 skill 提供完整的深度学习训练工作流，包括：

- 📋 **项目规划** - 制定计划、分解任务、评估风险
- 🏗️ **架构设计** - 设计网络、选择Backbone、分析复杂度
- ⚙️ **算法设计** - 设计损失函数、配置优化器、定义评估指标
- 🚀 **性能优化** - 解决显存OOM、加速训练、优化资源
- 📊 **精度调优** - 解决过拟合、应用Bag of Tricks、提升精度
- ✅ **测试评估** - 编写评估脚本、设计测试用例、验证性能
- 📖 **文档编写** - 编写README、API文档、使用教程
- 🔍 **架构搜索** - NAS搜索最优架构、模型压缩

## 8个专业Agent

1. **project-planner** - 项目规划专家
2. **model-architect** - 模型架构设计专家
3. **algorithm-designer** - 算法设计专家
4. **performance-tuner** - 性能调优专家
5. **accuracy-tuner** - 精度调优专家
6. **test-engineer** - 测试开发专家
7. **doc-writer** - 文档编写专家
8. **nas-specialist** - 网络架构搜索专家

## 目录结构

```
project/
├── doc/                  # 项目文档
├── plan/                 # 开发计划
├── config/               # 配置文件
├── model/                # 模型结构
├── loss/                 # 损失函数
├── util/                 # 工具函数
├── engine/               # 训练引擎
├── datalist/             # 数据列表
├── dataset/              # 数据处理
├── metrics/              # 评价指标
├── log/                  # 日志和可视化
├── checkpoint/           # 模型检查点
└── test/                 # 测试代码
```

## 许可证

MIT License

## 作者

Weihang (DJI)

## 联系方式

- GitHub: https://github.com/ahangchen
