# 肥啾向前飞 | FatBird Fly Forward
基于 HTML5 Canvas 开发的轻量级休闲小游戏 | Lightweight Casual Game Developed with HTML5 Canvas

---

## 项目介绍 | Project Introduction
《肥啾向前飞》是一款基于 Canvas 开发的轻量级 HTML5 休闲小游戏，针对移动端与桌面端做了深度适配优化。游戏内置多场景、多难度、多角色皮肤定制体系，结合粒子特效与 Web Audio API 动态音效，在保证流畅体验的同时兼顾视觉与听觉的沉浸感，所有功能均基于原生 JavaScript 实现，无需依赖任何框架或构建工具。

FatBird Fly Forward is a lightweight HTML5 casual game developed with Canvas. It features in-depth adaptive optimization for mobile and desktop devices, with a built-in customization system for multiple scenes, difficulty levels, and character skins. Combined with particle effects and dynamic sound effects via Web Audio API, the game ensures smooth experience while delivering immersive visual and auditory feedback. All functions are implemented with vanilla JavaScript, without relying on any frameworks or build tools.

---

## 核心功能 | Core Features
- 全设备自适应布局，适配手机、平板、电脑多终端
- 内置多游戏场景，支持视觉风格自由切换
- 多档位难度调节，可自定义游戏核心参数
- 多款角色皮肤，支持配色自定义
- 粒子特效 + 动态音效，沉浸式游戏体验
- 本地存储，自动保存玩家设置
- 优化键鼠/触摸交互，屏蔽移动端误触操作

- Fully adaptive layout for mobile, tablet and desktop devices
- Multiple built-in game scenes with customizable visual styles
- Multi-level difficulty adjustment with customizable core game parameters
- Various character skins with custom color schemes
- Particle effects and dynamic sound effects for immersive experience
- Local storage to automatically save player settings
- Optimized keyboard/mouse/touch interaction, disable misoperations on mobile

---

## 技术栈 | Tech Stack
- 渲染：HTML5 Canvas
- 开发：原生 JavaScript (ES6+)
- 音频：Web Audio API
- 存储：localStorage
- 样式：CSS3

- Rendering: HTML5 Canvas
- Development: Vanilla JavaScript (ES6+)
- Audio: Web Audio API
- Storage: localStorage
- Style: CSS3

---

## 运行方式 | How to Run
1. 下载项目文件，使用现代浏览器打开 `forward_fly_V7.html`
2. 首次运行点击页面激活音频（浏览器策略限制）
3. 支持本地运行，也可部署至静态服务器

1. Download the project files and open `forward_fly_V7.html` with a modern browser
2. Click the page to activate audio on first run (browser policy restriction)
3. Supports local running and deployment to static servers

---

## 自定义修改 | Customization
- 调整游戏难度：修改 `DIFFICULTY_CONFIG` 配置
- 自定义角色皮肤：扩展 `SKINS` / `SKIN_CONFIG`
- 新增游戏场景：修改 `SCENES` 常量并完善视觉音效逻辑
- 优化视觉效果：调整粒子、画布、障碍物参数

- Adjust game difficulty: Modify `DIFFICULTY_CONFIG`
- Customize skins: Extend `SKINS` / `SKIN_CONFIG`
- Add new scenes: Modify `SCENES` and update visual/audio logic
- Optimize visuals: Adjust particle, canvas and obstacle parameters

---

## 注意事项 | Notes
- 推荐使用 Chrome / Firefox 等现代浏览器运行
- 移动端支持触摸操作，桌面端支持键鼠操作
- 纯前端项目，无需联网、无依赖、无广告

- Recommended to run with modern browsers (Chrome / Firefox)
- Supports touch operation on mobile, keyboard and mouse on desktop
- Pure front-end project, no internet, no dependencies, no ads
