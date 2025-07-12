# Uber Login Page Clone (Vue 3)

这是一个使用 Vue 3 + Vite 构建的 Uber 登录页面克隆项目，模仿了最新的 auth.uber.com 登录页面设计风格。

## 功能特点

- 🎨 **现代化设计** - 采用最新的 Uber 登录页面简洁设计风格
- 📱 **响应式设计** - 完美适配桌面端、平板和移动设备
- ⚡ **Vue 3 + Vite** - 使用最新的前端技术栈，提供极速开发体验
- 🔄 **丰富交互** - 表单验证、loading 状态、hover 效果等
- 🌍 **国际化支持** - 支持多个国家和地区的电话号码格式
- 🎯 **简洁布局** - 采用居中单栏布局，更符合现代 UI 趋势

## 设计改进

相比之前的版本，这个 Vue 3 版本采用了更加现代化和简洁的设计：

### 🎨 **视觉改进**
- **更大的标题** - 42px 大标题，增强视觉冲击力
- **更大的输入框** - 增加 padding，提升用户体验
- **简化布局** - 移除右侧装饰，专注核心功能
- **更厚的边框** - 2px 边框提升现代感
- **渐变阴影** - 精致的交互反馈

### 📱 **交互优化**
- **Focus 状态** - 清晰的焦点指示和边框变化
- **Hover 效果** - 按钮上浮效果，增强交互感
- **Loading 动画** - 优雅的加载状态展示
- **响应式断点** - 针对不同设备的精确优化

## 页面结构

- **顶部导航栏** - Uber Logo + 导航菜单（Company, Safety, Help）
- **主要内容区域**：
  - 居中的大标题
  - 电话号码输入框（带国家代码选择器）
  - Continue 按钮（带禁用状态）
  - 分隔线
  - Google/Apple 社交登录按钮
  - 用户协议说明文字
- **底部链接** - Privacy, Accessibility, Terms

## 技术栈

- **Vue 3** - 前端框架（Composition API）
- **Vite** - 构建工具和开发服务器
- **CSS3** - 现代样式（CSS 变量、Grid、Flexbox、动画）
- **Inter 字体** - 与 Uber 官方保持一致

## 快速开始

### 1. 安装依赖

\`\`\`bash
npm install
\`\`\`

### 2. 启动开发服务器

\`\`\`bash
npm run dev
\`\`\`

项目将在 http://localhost:3000 启动

### 3. 构建生产版本

\`\`\`bash
npm run build
\`\`\`

### 4. 预览生产版本

\`\`\`bash
npm run preview
\`\`\`

## 项目结构

\`\`\`
uber-login-vue/
├── public/
├── src/
│   ├── App.vue          # 主应用组件
│   ├── style.css        # 全局样式和 CSS 变量
│   └── main.js          # 应用入口
├── index.html           # HTML 模板
├── package.json         # 项目配置
├── vite.config.js       # Vite 配置
└── README.md           # 项目说明
\`\`\`

## 设计系统

### CSS 变量
项目使用统一的 CSS 变量系统：

\`\`\`css
:root {
  --uber-black: #000000;
  --uber-white: #ffffff;
  --uber-gray-*: #颜色值;
  --border-radius: 8px;
  --border-radius-lg: 12px;
  --transition: all 0.2s ease;
}
\`\`\`

### 响应式断点
- **桌面端** (>768px): 完整布局和导航
- **平板端** (≤768px): 调整间距和字体大小
- **移动端** (≤480px): 垂直堆叠输入框，隐藏导航

### 交互状态
- **Normal**: 基础状态
- **Hover**: 颜色变化 + 上浮效果
- **Focus**: 边框高亮 + 阴影
- **Disabled**: 灰色状态 + 禁用光标
- **Loading**: 旋转动画 + 文字变化

## Vue 3 特性

### Composition API
项目使用 Vue 3 的 Composition API：

\`\`\`javascript
import { ref } from 'vue'

export default {
  setup() {
    const phoneNumber = ref('')
    const isLoading = ref(false)
    
    return {
      phoneNumber,
      isLoading
    }
  }
}
\`\`\`

### 响应式状态管理
- \`phoneNumber\` - 电话号码输入
- \`selectedCountry\` - 国家代码选择
- \`isLoading\` - 加载状态
- \`isInputFocused\` - 输入框焦点状态

## 浏览器支持

支持所有现代浏览器：
- Chrome (最新版本)
- Firefox (最新版本)
- Safari (最新版本)
- Edge (最新版本)

## 开发说明

这是一个演示项目，仅用于学习和展示目的。所有的表单提交和社交登录都是模拟的，不会进行真实的用户验证或数据传输。

## 特色功能

- ✅ **完美的 Uber 风格复制** - 精确模仿官方设计
- ✅ **现代化的 Vue 3 架构** - 使用最新的 Composition API
- ✅ **优雅的加载状态** - 带旋转动画的处理状态
- ✅ **完整的表单验证** - 实时验证和状态反馈
- ✅ **精致的微交互** - hover、focus、disabled 状态
- ✅ **完美的响应式** - 适配所有设备尺寸

## License

MIT License # uber
