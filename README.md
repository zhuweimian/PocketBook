﻿# GerenceShi - 个人财务管理应用

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Android](https://img.shields.io/badge/Platform-Android-green.svg)](https://developer.android.com)
[![Kotlin](https://img.shields.io/badge/Language-Kotlin-blue.svg)](https://kotlinlang.org)

一个功能完整的Android个人财务管理应用，支持本地数据存储、离线操作和AI智能助手。

## ✨ 功能特性
###本地模型的AI功能做不好，因为我不懂代码(所有代码都由AI完成)，但是API接口的AI模型能正常使用
- **其他功能目前可以正常使用**
  
### 📊 核心财务功能
- **交易记录管理** - 收入/支出记录，分类管理
- **信用卡管理** - 多卡片管理，账单提醒
- **贷款管理** - 贷款记录，还款计划
- **预算管理** - 预算设置，超支提醒
- **统计报告** - 图表分析，财务洞察
- **数据导出** - CSV格式导出

### 🤖 AI智能助手
- **本地AI推理** - 支持MNN、ONNX、TensorFlow Lite等格式
- **智能对话** - 财务咨询，预算建议
- **隐私保护** - 完全本地运行，数据不上传
- **多模型支持** - 可下载不同大小的AI模型

### 🔒 数据安全
- **本地存储** - 所有数据存储在设备本地
- **离线操作** - 无需网络连接即可使用
- **数据备份** - 本地备份/恢复功能
- **隐私优先** - 不收集任何个人数据

### 🎨 用户体验
- **现代UI设计** - Material Design 3
- **中国风元素** - 云纹图案，优雅配色
- **声音反馈** - 操作音效，提升体验
- **流畅动画** - 页面转场，交互动效

## 🛠️ 技术栈

- **开发语言**: Kotlin
- **UI框架**: Jetpack Compose
- **数据库**: Room (SQLite)
- **架构**: MVVM + Repository Pattern
- **AI框架**: MNN, ONNX Runtime, TensorFlow Lite
- **网络**: OkHttp + Retrofit
- **依赖注入**: Hilt
- **异步处理**: Coroutines + Flow

## 📱 系统要求

- **最低版本**: Android 7.0 (API 24)
- **推荐版本**: Android 10+ (API 29+)
- **架构支持**: ARM64, ARMv7
- **存储空间**: 100MB+ (不含AI模型)
- **内存要求**: 4GB+ RAM (推荐6GB+)

## 🚀 快速开始

### 环境准备

1. **Android Studio**: Arctic Fox 或更高版本
2. **JDK**: 11 或更高版本
3. **Android SDK**: API 34
4. **NDK**: 25.1.8937393 (用于AI模型)

### 构建步骤

```bash
# 1. 克隆项目
git clone https://github.com/yourusername/gerenceshi.git
cd gerenceshi

# 2. 创建local.properties文件
echo "sdk.dir=/path/to/your/android/sdk" > local.properties

# 3. 构建项目
./gradlew assembleDebug

# 4. 安装到设备
./gradlew installDebug
```

### AI模型配置 (可选)

1. **下载AI模型** (推荐Qwen2-1.5B-MNN)
2. **放置到设备存储**: `/storage/emulated/0/models/`
3. **在应用中配置**: AI设置 → 选择模型路径

## 📖 使用指南

### 基础功能

1. **添加交易记录**
   - 点击主页"+"按钮
   - 选择收入/支出类型
   - 填写金额、分类、备注

2. **查看统计报告**
   - 进入"统计"页面
   - 查看月度/年度报告
   - 分析支出分布

3. **使用AI助手**
   - 点击"AI助手"
   - 询问财务问题
   - 获取个性化建议

### 高级功能

- **预算管理**: 设置月度预算，跟踪支出
- **信用卡管理**: 管理多张信用卡，设置还款提醒
- **数据导出**: 导出CSV文件进行进一步分析

## 🤝 贡献指南

我们欢迎所有形式的贡献！

### 如何贡献

1. **Fork** 本项目
2. **创建** 功能分支 (`git checkout -b feature/AmazingFeature`)
3. **提交** 更改 (`git commit -m 'Add some AmazingFeature'`)
4. **推送** 到分支 (`git push origin feature/AmazingFeature`)
5. **创建** Pull Request

### 开发规范

- 遵循 [Kotlin编码规范](https://kotlinlang.org/docs/coding-conventions.html)
- 使用 [Conventional Commits](https://www.conventionalcommits.org/)
- 添加适当的测试用例
- 更新相关文档

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 🙏 致谢

- [MNN](https://github.com/alibaba/MNN) - 高性能深度学习推理框架
- [ModelScope](https://modelscope.cn) - AI模型社区
- [Material Design](https://material.io) - 设计系统
- [Jetpack Compose](https://developer.android.com/jetpack/compose) - 现代UI工具包

## 📞 联系方式

- **Issues**: [GitHub Issues](https://github.com/yourusername/gerenceshi/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/gerenceshi/discussions)

---

⭐ 如果这个项目对您有帮助，请给我们一个星标！

### 📊 财务概览
- 实时显示月度收入和支出统计
- 信用卡余额总览
- 贷款余额监控
- 美观的卡片式布局展示

### 💰 交易管理
- 记录日常收入和支出
- 分类管理交易记录
- 快速添加常用交易
- 交易历史查询和筛选

### 💳 信用卡管理
- 多张信用卡信息管理
- 账单日和还款日提醒
- 信用额度和当前余额跟踪
- 消费记录关联

### 🏦 贷款管理
- 多种贷款类型支持（个人、房贷、车贷等）
- 还款计划跟踪
- 利息计算
- 剩余本金监控

## 技术架构

### 开发技术栈
- **语言**: Kotlin
- **UI框架**: Jetpack Compose
- **架构模式**: MVVM + Repository Pattern
- **数据库**: Room Database (SQLite)
- **依赖注入**: Hilt
- **导航**: Navigation Compose

### 项目结构
```
app/
├── data/
│   ├── entity/          # 数据实体类
│   ├── dao/             # 数据访问对象
│   ├── database/        # 数据库配置
│   └── repository/      # 数据仓库层
├── di/                  # 依赖注入模块
├── ui/
│   ├── components/      # 可复用UI组件
│   ├── navigation/      # 导航配置
│   ├── screens/         # 各功能界面
│   └── theme/           # 主题配置
└── MainActivity.kt      # 主活动
```

## 设计特点

### 🎨 现代化UI设计
- Material Design 3 设计语言
- 美观的卡片布局，间距适中
- 清晰的视觉层次和颜色搭配
- 流畅的动画效果

### 📱 用户体验
- 直观的底部导航
- 快捷操作按钮
- 响应式设计
- 离线优先的设计理念

### 🔒 数据安全
- 完全本地存储，无需网络连接
- 数据隐私保护
- 支持设备间数据传输
- 排除云备份敏感数据

## 安装和运行

### 环境要求
- Android Studio Arctic Fox 或更高版本
- Android SDK 24 或更高版本
- Kotlin 1.9.10 或更高版本

### 构建步骤

#### 方法一：使用Android Studio（推荐）
1. 下载并安装Android Studio
2. 打开项目文件夹 `d:\gerenceshi`
3. 等待Gradle同步完成
4. 连接Android设备或启动模拟器
5. 点击运行按钮（▶️）

#### 方法二：使用命令行
```cmd
cd d:\gerenceshi
gradlew.bat assembleDebug
gradlew.bat installDebug
```

#### 方法三：使用批处理脚本
双击运行 `build_and_run.bat` 文件

> 💡 **提示**: 详细的运行说明请查看 `运行指南.md` 文件

## 应用使用说明

### 首次启动
应用首次启动时会自动创建示例数据，包括：
- 默认的收入和支出分类
- 几条示例交易记录
- 示例信用卡信息
- 示例贷款信息

### 主要功能使用

#### 1. 仪表盘
- 查看月度收入支出统计
- 查看信用卡和贷款余额概览
- 查看最近的交易记录
- 使用快捷操作按钮

#### 2. 交易管理
- 点击右下角的"+"按钮添加新交易
- 选择交易类型（收入/支出）
- 输入金额、描述和选择分类
- 选择交易日期并保存

#### 3. 信用卡管理
- 查看所有信用卡的详细信息
- 查看当前余额和信用额度
- 查看账单日和还款日信息

#### 4. 贷款管理
- 查看所有贷款的详细信息
- 查看剩余本金和月还款额
- 查看下次还款日期和利率信息

## 功能规划

### 已实现功能
- ✅ 基础项目架构
- ✅ 数据库设计和实现
- ✅ 主要界面框架
- ✅ 导航系统
- ✅ 基础UI组件
- ✅ 交易添加功能
- ✅ 信用卡展示界面
- ✅ 贷款展示界面
- ✅ 示例数据初始化
- ✅ 美观的卡片式布局

### 待实现功能
- 🔄 交易编辑和删除功能
- 🔄 信用卡添加和编辑
- 🔄 贷款添加和编辑
- 🔄 贷款计算器
- 🔄 数据可视化图表
- 🔄 数据筛选和搜索
- 🔄 数据导入导出
- 🔄 提醒和通知功能
- 🔄 数据备份和恢复
- 🔄 主题切换功能

## 贡献指南

欢迎提交Issue和Pull Request来改进这个项目。

## 许可证

本项目采用MIT许可证。
