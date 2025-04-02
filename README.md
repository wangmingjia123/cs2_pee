# CS小蜜蜂传奇 - 夺冠之路

一个展示CS:GO战队夺冠历程的现代化网站，使用Vue3和Three.js构建。

## 项目特点

- 🎨 现代化UI设计
  - 深色调主题
  - 毛玻璃效果
  - 响应式布局
- 🎮 丰富的交互体验
  - 3D蜂巢网格背景
  - 视差滚动效果
  - 鼠标悬停动画
- 🌙 自动暗黑模式
  - 跟随系统主题
  - 平滑切换效果
- 📱 移动端适配
  - 自适应布局
  - 触摸优化

## 技术栈

- Vue 3
- Vite
- Three.js
- GSAP
- CSS3

## 项目结构

```
cs-bee-legend/
├── public/              # 静态资源
│   └── images/          # 图片资源
├── src/
│   ├── components/      # Vue组件
│   │   ├── HeroSection.vue
│   │   ├── EarlyStagesSection.vue
│   │   ├── MidTournamentSection.vue
│   │   ├── FinalsSection.vue
│   │   └── VictorySection.vue
│   ├── App.vue         # 主组件
│   └── main.js         # 入口文件
├── index.html          # HTML模板
└── package.json        # 项目配置
```

## 运行项目

1. 安装依赖
```bash
npm install
```

2. 开发模式运行
```bash
npm run dev
```

3. 构建生产版本
```bash
npm run build
```

## 在线演示

访问 [CS小蜜蜂传奇](https://wangmingjia123.github.io/cs2_pee/) 查看在线演示。

## 部署说明

项目已部署在GitHub Pages，通过GitHub Actions自动构建和部署。

## 贡献指南

1. Fork 项目
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建Pull Request

## 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 联系方式

如有任何问题或建议，欢迎提交Issue或Pull Request。
