我来为这个项目写一个开源介绍，需要包含：
1. 项目名称和描述
2.特色功能
3. 技术栈
4. 使用说明
5.贡献指南
6. 许可证
7.联系方式

风格要保持Y2K、温暖、有趣，符合项目调性。

```markdown
# XUSN·SPACE - Y2K风格个人主页

<div align="center">
  <img src="https://img.shields.io/badge/Y2K-复古未来-ff6b9d?style=for-the-badge&logoColor=white" alt="Y2K Style">
  <img src="https://img.shields.io/badge/Tailwind-CSS-00f5d4?style=for-the-badge&logo=tailwindcss" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/JavaScript-ES6+-f8b500?style=for-the-badge&logo=javascript" alt="JavaScript">
  <img src="https://img.shields.io/badge/License-MIT-9b5de5?style=for-the-badge" alt="MIT License">
</div>

## 🌟项目介绍

**XUSN·SPACE** 是一个充满Y2K复古未来风格的个人主页项目。它不仅仅是一个展示页面，更是一个温暖、有趣、充满交互的数字空间。

> 设计理念：让每一次点击都充满温度，让网页不再是冰冷的信息载体。

## ✨ 特色功能

### 🎨 视觉设计
- **Y2K美学**：圆角、粗边框、渐变色彩、像素风格
- **动态背景**：移动网格 + 几何图形装饰
- **玻璃拟态**：半透明磨砂效果卡片
- **温暖配色**：粉色、黄色、青色、紫色的治愈配色方案

### 🎮 交互体验
- **智能导航栏**：上滑隐藏，下滑出现，贴合顶部
- **涟漪按钮**：每次点击都有水波纹反馈
- **3D翻页卡片**：点击翻转查看"关于我"和技能
- **QQ头像交互**：点击切换4种形状（圆角→圆形→方形→圆形）
- **随机一言**：调用hitokoto API，点击刷新
- **作品集图片**：随机风景API，每次访问都不同

### 📱 响应式设计
- 完美适配手机、平板、桌面
- 智能导航栏在不同屏幕尺寸下的表现
- 流畅的动画过渡

### 🔧 实用功能
- **留言表单**：一键发送邮件
- **公众号二维码**：动态生成
- **社交链接**：邮箱、小红书、GitHub
- **404页面**：独立设计的404页面

## 🛠️ 技术栈

### 前端
- **HTML5** - 语义化结构
- **Tailwind CSS** - 快速样式开发
- **JavaScript** - 交互逻辑
- **VT323字体** - 像素风格字体

### API
- **Hitokoto** - 随机一言
- **Picsum** - 随机风景图片
- **QQ头像API** - 动态头像
- **QRCode.js** - 二维码生成

##🚀 快速开始

### 1. 下载项目
```bash
git clone https://github.com/yourusername/xusn-space.git
cd xusn-space
```

### 2. 自定义配置
编辑HTML文件中的以下部分：

```javascript
// 1. QQ头像（第148行）
src="https://q.qlogo.cn/headimg_dl?bs=YOUR_QQ&img_type=10&size=100"

// 2. 公众号二维码链接（第538行）
const wechatURL = 'http://weixin.qq.com/r/你的公众号链接';

// 3. 邮箱地址（第578行）
const mailtoLink = `mailto:你的邮箱@xxx.com...

// 4.社交链接（第600-615行）
href="你的小红书链接"
href="你的GitHub链接"
```

### 3. 部署
可以直接上传到：
- GitHub Pages
- Vercel
- Netlify
- 任何静态托管服务

## 📁项目结构

```
xusn-space/
├── index.html          # 主页面
├── 404.html            # 404错误页面
├── README.md           # 项目说明
└── screenshots/        # 预览截图（可选）
```

## 🎨 设计亮点

### 1. 智能导航栏
-初始状态：居中圆角卡片
- 滚动100px后：贴顶，变为完整宽度
- 上滑隐藏，下滑显示
- 悬停放大效果

### 2. 翻页卡片
- 正面：关于我（橙粉渐变）
- 背面：自我介绍 + 技能列表- 3D翻转动画
- 点击交互

### 3. 头像彩蛋
- 默认：圆角矩形 + 浮动动画
- 点击1次：圆形 + 脉冲
- 点击2次：方形 + 摇晃
- 点击3次：圆形 + 弹跳
- 点击4次：回到默认

### 4. 随机内容
- 一言API：每次点击获取新句子
- 作品图片：随机风景，每次不同
- 颜色变化：交互时动态变色

## 🤝 贡献指南

欢迎贡献！你可以通过以下方式帮助项目：

### 提交Issue
- 报告bug
- 提出新功能建议
- 分享使用体验

### 提交PR
1. Fork项目
2. 创建你的分支 (`git checkout -b feature/your-feature`)
3. 提交更改 (`git commit -m 'Add your feature'`)
4. 推送到分支 (`git push origin feature/your-feature`)
5. 创建Pull Request

### 代码规范
- 保持Y2K设计风格
- 使用语义化HTML
- 添加必要的注释
- 测试响应式兼容性

## 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

```text
MIT License

Copyright (c) 2023 XUSN

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 📞 联系方式

- **邮箱**：[un@xusn.dev](mailto:un@xusn.dev)
- **公众号**：扫码关注（在页面内）
- **小红书**：[搜索 XUSN](https://xhslink.com/m/3QRw1wru5Eh)
- **GitHub**：[@XiaoQius](https://github.com/XiaoQius)

## 🙏 致谢

- [Tailwind CSS](https://tailwindcss.com) - 优秀的CSS框架
- [Hitokoto](https://hitokoto.cn) - 提供随机一言
- [Picsum](https://picsum.photos) - 随机图片服务
- [QRCode.js](https://github.com/davidshimjs/qrcodejs) - 二维码生成
- [VT323字体](https://fonts.google.com/specimen/VT323) - 像素字体

## 🌈 为什么开源？

因为Y2K风格太酷了！希望更多人能拥有一个既复古又现代的个人主页。如果你喜欢这个项目，请：
- ⭐ Star一下
- 🔄 Fork一份
- 📤 分享给朋友

---

**Made with ❤️ by XUSN | Y2K Design & Code**

<div align="center">
  <img src="https://img.shields.io/badge/Keep_Coding-保持热爱-ff6b9d?style=for-the-badge" alt="Keep Coding">
  <img src="https://img.shields.io/badge/Keep_Designing-持续创造-00f5d4?style=for-the-badge" alt="Keep Designing">
</div>
```

这个开源介绍包含了：

1. **项目简介** - 清晰的定位
2. **特色功能** - 详细的亮点
3. **技术栈** - 使用的技术
4. **快速开始** - 使用教程
5. **设计亮点** -独特功能详解
6. **贡献指南** - 如何参与
7. **许可证** - MIT开源
8. **联系方式** - 多种渠道
9. **致谢** - 社区贡献

风格保持了：
- ✅ Y2K美学
- ✅ 温暖语言
- ✅趣味emoji
- ✅ 实用信息
- ✅社区友好
