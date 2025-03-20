# AI集合工具应用原型

这是一个使用HTML和Tailwind CSS构建的AI集合工具应用的高保真原型设计。

## 项目概述

这个项目是一个AI集合工具应用的原型设计，模拟了用户在移动设备上使用各种AI功能的体验。原型使用纯HTML和Tailwind CSS构建，没有使用任何JavaScript框架。

## 核心功能

- **AI助手** - 智能对话功能
- **创意工具** - AI创意生成功能，包括图像、故事、音乐等
- **个人中心** - 用户信息和设置管理

## 文件结构

```
.
├── index.html          # 主入口，使用iframe嵌套其他页面
├── home.html           # 首页，展示AI工具集合
├── assistant.html      # AI助手页面
├── creative.html       # 创意工具页面
├── profile.html        # 个人中心页面
├── css/
│   └── custom.css      # 自定义样式
├── js/                 # JavaScript文件夹 (暂未使用)
└── images/             # 图片文件夹 (使用外部图片链接)
```

## 技术栈

- HTML5
- Tailwind CSS
- Font Awesome 图标
- 使用了Unsplash的图片资源

## 如何使用

1. 直接打开 `index.html` 文件查看完整应用
2. 也可以单独打开各个页面查看不同功能模块：
   - `home.html` - 首页
   - `assistant.html` - AI助手
   - `creative.html` - 创意工具
   - `profile.html` - 个人中心

## 设计说明

- 使用iPhone 15的尺寸和样式作为设计基准
- 采用现代化的UI设计，符合移动端用户习惯
- 使用Tailwind CSS实现响应式设计和现代UI效果
- 所有页面使用了统一的设计语言和配色方案

## Figma转换说明

这个HTML原型设计可以很容易地导入到Figma中进行进一步编辑：

1. 在Figma中创建新的设计文件
2. 使用"导入"功能导入HTML文件
3. 调整视图和组件位置
4. 根据需要进行进一步的设计调整

## 注意事项

- 这是一个静态原型，没有实现真正的功能交互
- 所有的状态和数据都是模拟的，不会真正保存
- 按钮和链接可以点击，但不会触发真正的操作，只用于展示UI效果 