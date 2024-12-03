# flutter_selfhostedModel

## 关于这个项目
这是一个由 Flutter 框架搭建的大模型聊天软件，旨在提供一个多功能的聊天体验。项目的主要功能包括：

- **用户输入**：
  - 语音自动识别：支持通过麦克风输入语音，并自动转换为文字。
  - 文字输入：用户可以直接在聊天界面输入文字进行交流。
  - 图片输入：允许用户上传图片，系统会对图片进行处理并生成相应的文本或响应。

- **模型调用**：
  - ollama 服务器 API 调用：通过 ollama 服务器获取高级语言模型的响应，增强聊天体验。
  - stable diffusion webui API 调用：利用 stable diffusion 生成高质量的图像，丰富聊天内容。

- **模型输出**：
  - vits 模型提供的 TTS 输出：将文本转换为自然的语音输出，提升用户体验。

- **其他功能**：
  - live2d 看板娘功能：集成 live2d 模型，提供一个生动的虚拟角色与用户互动，增加趣味性和沉浸感。

该项目支持跨多个平台，包括但不限于 Android、iOS 和 Web。

## 待办事项 (TODO)

## 技术栈
- **前端**：Flutter
- **后端**：ollama 服务器、stable diffusion webui
- **语音处理**：vits 模型

## 安装与运行
1. 克隆仓库：
   ```bash
   git clone https://github.com/greenhandzdl/flutter_selfhostedModel.git
   cd flutter_selfhostedModel
   ```

2. 安装依赖：
   ```bash
   flutter pub get
   ```

3. 测试应用：
   ```bash
   flutter run
   ```

## 贡献
欢迎贡献代码！请遵循以下步骤：
1. Fork 本仓库。
2. 创建一个新的分支：
   ```bash
   git checkout -b feature/new-feature
   ```
3. 提交你的更改：
   ```bash
   git commit -m "Add new feature"
   ```
4. 推送分支：
   ```bash
   git push origin feature/new-feature
   ```
5. 提交 Pull Request。

## 许可证
本项目采用 MIT 许可证，详情参见 [LICENSE](LICENSE) 文件。

## 联系方式
如果有任何问题或建议，请联系 [](greenhandzdl@greenhandzdl.moe) 或在 GitHub 上创建 Issue。
