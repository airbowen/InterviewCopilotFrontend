# AI面试助手平台

一个现代化的AI驱动面试练习平台，支持多种面试模式和IELTS口语评测。

## 🌟 核心功能

### 📱 用户认证
- **手机验证登录** - 安全的短信验证码认证系统
- **会话管理** - JWT令牌管理用户状态

### 🎤 多种面试模式
- **语音模式**: 手动控制录音，适合安静环境
- **屏幕共享模式**: 自动语音检测，支持系统音频
- **高级模式**: 智能过滤，仅检测问题内容

### 🤖 AI面试功能
- **实时AI对话** - 智能面试官问答系统
- **语音转文字** - 高精度语音识别
- **多维度分析** - 语速、词汇、逻辑、结构评估

### 📊 IELTS口语评测
- **专业评分系统** - 5维度雅思口语分析
- **雷达图可视化** - 直观展示能力分布
- **详细反馈建议** - 个性化改进方案

## 🛠️ 技术栈

- **前端**: React 18 + TypeScript + Tailwind CSS
- **路由**: React Router DOM
- **图表**: Recharts
- **图标**: Lucide React + React Icons
- **构建工具**: Vite

## 🚀 快速开始

### 安装依赖
```bash
npm install
```

### 启动开发服务器
```bash
npm run dev
```

### 构建生产版本
```bash
npm run build
```

## 📁 项目结构

```
src/
├── components/          # 可复用组件
│   ├── Navigation.tsx   # 导航栏
│   ├── Footer.tsx       # 页脚
│   └── LanguageToggle.tsx # 语言切换
├── contexts/           # React上下文
│   ├── AuthContext.tsx # 认证状态管理
│   └── LanguageContext.tsx # 多语言支持
├── pages/              # 页面组件
│   ├── Home.tsx        # 首页
│   ├── Guide.tsx       # 使用指南
│   ├── Login.tsx       # 登录页面
│   ├── ModeSelection.tsx # 模式选择
│   ├── Interview.tsx   # AI面试
│   ├── Analysis.tsx    # 面试分析
│   └── IELTSEvaluation.tsx # IELTS评测
├── hooks/              # 自定义Hooks
│   └── useRecording.ts # 录音功能
└── types/              # TypeScript类型定义
    └── index.ts
```

## 🎯 主要页面

### 🏠 首页 (`/`)
- 平台介绍和功能展示
- 统计数据展示
- 快速导航入口

### 📖 使用指南 (`/guide`)
- 三种面试模式详细说明
- 设置步骤指导
- 浏览器兼容性说明

### 🔐 登录页面 (`/login`)
- 手机号验证码登录
- 双步验证流程
- 安全提示信息

### ⚙️ 模式选择 (`/mode`)
- 面试模式选择
- 个人信息配置
- 面试参数设置

### 🎤 AI面试 (`/interview`)
- 实时语音录制
- AI智能问答
- 聊天式交互界面

### 📊 面试分析 (`/analysis`)
- 多维度性能评估
- 详细分析报告
- 改进建议

### 🏆 IELTS评测 (`/ielts`)
- 雅思口语三部分练习
- 5维度能力分析
- 雷达图可视化展示

## 🌐 多语言支持

支持中文和英文双语切换，覆盖所有界面文本和提示信息。

## 📱 响应式设计

完全适配移动端和桌面端，提供一致的用户体验。

## 🎨 设计特色

- **现代化UI** - 采用毛玻璃效果和渐变设计
- **流畅动画** - 丰富的交互动效和过渡效果
- **直观导航** - 清晰的信息架构和导航结构
- **无障碍设计** - 符合可访问性标准

## 📄 许可证

MIT License# InterviewCopilotFrontend
