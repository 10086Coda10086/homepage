# README - My Personal Homepage

这个项目是我的个人主页项目，基于 [ZYYO666/homepage](https://github.com/ZYYO666/homepage) 进行开发，为我的博客提供优雅简约的主页入口。

## 项目预览



访问地址：[https://realityme.top](https://realityme.top)

## 主要特性

✨ **多主题支持**
- 内置5套精美亮色主题
- 暗夜模式切换
- CSS变量实现主题系统，无需JS依赖

🎨 **视觉体验**
- 卡片模糊效果（背景整体模糊或卡片模糊可选）
- 卡片半透明效果
- 精心设计的动画过渡效果
- 响应式设计（桌面端4列/移动端2列或1列）

⚡️ **性能优化**
- 使用字体图标替代图片资源
- 所有路径使用相对路径
- 优化加载动画和交互体验

🔧 **便捷定制**
- 通过 `/static/root.css` 轻松修改主题
- 通过 `/static/style.css` 自定义样式
- 简单替换图标和头像资源

## 技术栈

- HTML5
- CSS3 (含CSS变量)
- JavaScript (ES6)
- 纯原生实现，无框架依赖

## 使用指南

1. 克隆本项目：
```bash
git clone https://github.com/10086Coda10086/homepage_stoped.git
```

2. 直接打开 `index.html` 即可运行

3. 自定义配置：
- 修改主题：编辑 `/static/root.css`
- 自定义样式：编辑 `/static/style.css`
- 更换头像：替换 `/static/img/favicon.ico`
- 修改交互逻辑：编辑 `/static/script.js`

## 项目结构

```
homepage_stoped/
├── static/                  # 静态资源
│   ├── root.css             # 主题变量配置
│   ├── style.css            # 主要样式文件
│   ├── script.js            # 交互逻辑
│   └── img/                 # 图片资源
│       └── favicon.ico      # 网站图标和头像
├── index.html               # 主页面
├── Caddyfile                # Web服务器配置
├── Dockerfile               # Docker镜像配置
└── docker-compose.yaml      # Docker容器配置
```

## 致谢

本项目灵感来源于：
- [xhofe](https://github.com/xhofe)
- [ddiu](https://github.com/ddiu8081)

特别感谢：
- [iconfont](https://www.iconfont.cn/) 提供图标资源
- Pacifico-Regular 和 Ubuntu-Regular 字体作者
- 鸿蒙字体提供支持

## 许可证

本项目基于 [MIT License](LICENSE) 开源。

## 注意事项

1. 本项目的图标均为SVG格式，可自由替换
2. 字体默认为鸿蒙字体，可通过CSS修改
3. 已停止新功能开发，专注于稳定性和性能优化

---

✨ **简约而不简单** - 一个优雅的个人主页入口，展示你的数字身份。
