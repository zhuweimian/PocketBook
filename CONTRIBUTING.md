# 贡献指南

感谢您对GerenceShi项目的关注！我们欢迎所有形式的贡献。

## 🤝 如何贡献

### 报告问题

如果您发现了bug或有功能建议：

1. 首先搜索 [现有Issues](https://github.com/yourusername/gerenceshi/issues) 确认问题未被报告
2. 创建新的Issue，请包含：
   - 清晰的标题和描述
   - 重现步骤（如果是bug）
   - 预期行为和实际行为
   - 设备信息（Android版本、设备型号等）
   - 相关截图或日志

### 提交代码

1. **Fork项目**
   ```bash
   git clone https://github.com/yourusername/gerenceshi.git
   cd gerenceshi
   ```

2. **创建功能分支**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **进行更改**
   - 遵循项目的编码规范
   - 添加必要的测试
   - 更新相关文档

4. **提交更改**
   ```bash
   git add .
   git commit -m "feat: add your feature description"
   ```

5. **推送分支**
   ```bash
   git push origin feature/your-feature-name
   ```

6. **创建Pull Request**
   - 提供清晰的PR标题和描述
   - 链接相关的Issues
   - 确保所有检查通过

## 📝 编码规范

### Kotlin代码风格

- 遵循 [Kotlin编码规范](https://kotlinlang.org/docs/coding-conventions.html)
- 使用4个空格缩进
- 行长度限制为120字符
- 使用有意义的变量和函数名

### 提交信息规范

使用 [Conventional Commits](https://www.conventionalcommits.org/) 格式：

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

**类型 (type):**
- `feat`: 新功能
- `fix`: 错误修复
- `docs`: 文档更新
- `style`: 代码格式化
- `refactor`: 代码重构
- `test`: 测试相关
- `chore`: 构建过程或辅助工具的变动

**示例:**
```
feat(ai): add MNN model support
fix(ui): resolve crash on transaction list
docs: update README with new features
```

### 代码审查

所有代码更改都需要通过代码审查：

- 确保代码质量和一致性
- 验证功能正确性
- 检查性能影响
- 确认文档完整性

## 🧪 测试

### 运行测试

```bash
# 运行单元测试
./gradlew test

# 运行UI测试
./gradlew connectedAndroidTest
```

### 添加测试

- 为新功能添加单元测试
- 为UI更改添加UI测试
- 确保测试覆盖率不降低

## 📚 开发环境设置

### 必需工具

- Android Studio Arctic Fox 或更高版本
- JDK 11 或更高版本
- Android SDK API 34
- NDK 25.1.8937393

### 项目设置

1. 克隆项目并打开Android Studio
2. 同步Gradle依赖
3. 创建 `local.properties` 文件
4. 配置签名密钥（如需要）

### 调试技巧

- 使用Android Studio的调试器
- 查看Logcat输出
- 使用Layout Inspector检查UI
- 利用Memory Profiler检查内存使用

## 🎯 贡献领域

我们特别欢迎以下方面的贡献：

### 功能开发
- 新的财务管理功能
- AI模型集成改进
- 用户体验优化
- 性能优化

### 文档
- API文档
- 用户指南
- 开发者文档
- 多语言支持

### 测试
- 单元测试
- 集成测试
- UI测试
- 性能测试

### 设计
- UI/UX改进
- 图标设计
- 动画效果
- 无障碍功能

## 🌍 国际化

如果您想帮助翻译项目：

1. 检查 `app/src/main/res/values-*/` 目录
2. 添加或更新字符串资源
3. 确保翻译准确和文化适宜
4. 测试不同语言下的UI布局

## 📞 联系方式

如果您有任何问题：

- 创建 [GitHub Issue](https://github.com/yourusername/gerenceshi/issues)
- 参与 [GitHub Discussions](https://github.com/yourusername/gerenceshi/discussions)

## 📄 许可证

通过贡献代码，您同意您的贡献将在MIT许可证下授权。

---

再次感谢您的贡献！🎉
