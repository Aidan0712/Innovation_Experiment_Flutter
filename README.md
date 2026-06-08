# 创新实验 Flutter 个性化项目

基于 Flutter 的创新实验个性化示例，展示了一个具有红色主题的互动学习助手界面。

## 项目信息

- **姓名**：Aidan
- **学号后四位**：0133
- **小组**：第 8 组

## 功能特点

### 个性化修改（6 处）

1. **AppBar 标题**：修改为 "🔥 创新实验 - 智能学习助手"，添加红色背景和阴影效果
2. **页面提示语**：修改为 "🔥 欢迎来到我的创新实验空间！"，添加红色渐变文字效果
3. **姓名和学号**：显示 "🎓 Aidan 0133｜小组：第8组"，添加红色边框卡片装饰
4. **按钮设计**：修改图标为圆形加号图标，文案改为 "点亮星星"，背景色改为红色渐变
5. **计数功能**：点击按钮后星星数量会增加，计数器显示 "收集的星星：X 颗"，带黄色星星图标
6. **界面装饰**：整体采用红色主题，包含渐变背景、卡片阴影、底部鼓励语和爱心图标

### 界面特效

- 🎨 红色渐变背景（浅红 → 粉红 → 浅红）
- ✨ 卡片阴影和发光效果
- 🔥 火焰主题图标
- ⭐ 星星计数器动画
- 💪 鼓励语和爱心装饰

## 技术栈

- Flutter SDK
- Material Design 3
- Dart

## 运行项目

### 方法一：使用 Edge 浏览器（推荐，避免代理问题）

```powershell
# 设置环境变量并运行
$env:NO_PROXY='localhost,127.0.0.1,::1'
$env:http_proxy=''
$env:https_proxy=''
flutter run -d edge --web-hostname 127.0.0.1 --web-port 5001
```

### 方法二：使用 Chrome 浏览器

```powershell
flutter run -d chrome
```

### 方法三：使用启动脚本

双击运行 `run_flutter.ps1` 或在终端中执行：

```powershell
powershell -ExecutionPolicy Bypass -File run_flutter.ps1
```

## 项目结构

```
Innovation_Experiment_Flutter/
├── lib/
│   └── main.dart              # 主程序代码
├── web/                       # Web 平台支持
│   ├── index.html
│   ├── manifest.json
│   └── icons/
├── windows/                   # Windows 桌面支持
│   ├── runner/
│   └── flutter/
├── test/                      # 测试文件
├── run_flutter.ps1            # 一键启动脚本
└── README.md                  # 项目说明文档
```

## 开发命令

- `flutter run` - 运行应用
- `flutter run -d chrome` - 指定 Chrome 浏览器运行
- `flutter run -d edge` - 指定 Edge 浏览器运行
- `r` - 热重载（在运行中的应用按 r 键）
- `R` - 热重启（在运行中的应用按 R 键）
- `q` - 退出应用

## 版本信息

- Flutter 版本：支持 Web 和 Windows 平台
- Material Design 3：✅ 已启用
- 响应式设计：✅ 支持多平台

## Git 提交记录

```powershell
git add lib/main.dart
git commit -m "feat: 红色主题界面个性化修改"
git push origin main
```

## 许可证

本项目仅用于创新实验课程学习参考。
