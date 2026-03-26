[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Three.js](https://img.shields.io/badge/Three.js-r162-black?logo=three.js)](https://threejs.org/)
[![GitHub Pages](https://img.shields.io/badge/Demo-Live-green)](https://masonthink.github.io/cuboid-unfold/)

# Cuboid Unfold -- Interactive 3D Unfolding Visualization

An interactive 3D visualization that animates the unfolding of a rectangular prism (cuboid) into its flat net. Designed as an educational tool to help students understand solid geometry concepts.

## Features

- Smooth 3D unfolding animation with adjustable speed
- Real-time dimension controls (length **a**, width **b**, height **c**)
- Each face displays its name, dimension formula, and computed area
- Surface area formula panel: `S = 2(ab + bc + ac)`
- Orbit controls: drag to rotate, scroll to zoom, right-click to pan
- Auto-play with fold/unfold cycling
- Single HTML file, works offline -- no build step required

## Net Layout

The cuboid unfolds into a cross-shaped net:

```
         +-------+
         |  Top  |
         | a x b |
+--------+-------+--------+-------+
|  Left  | Front | Right  | Back  |
| b x c  | a x c | b x c  | a x c |
+--------+-------+--------+-------+
         |Bottom |
         | a x b |
         +-------+
```

## Tech Stack

- [Three.js](https://threejs.org/) r162 -- 3D rendering
- Canvas API -- Dynamic face textures
- Pure HTML / CSS / JS -- No framework, no bundler

## Usage

Open `index.html` in any modern browser. No installation required.

## Status

Complete -- Functional single-page application.

## License

MIT

---

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Three.js](https://img.shields.io/badge/Three.js-r162-black?logo=three.js)](https://threejs.org/)
[![GitHub Pages](https://img.shields.io/badge/Demo-Live-green)](https://masonthink.github.io/cuboid-unfold/)

# Cuboid Unfold -- 长方体展开图交互式 3D 可视化

长方体展开为平面展开图的交互式 3D 动画演示，帮助学生理解立体几何中的展开图概念。

## 功能

- 平滑的 3D 展开动画，速度可调
- 实时调节尺寸参数（长 **a**、宽 **b**、高 **c**）
- 每个面显示名称、尺寸公式和计算面积
- 表面积公式面板：`S = 2(ab + bc + ac)`
- 轨道控制：拖拽旋转、滚轮缩放、右键平移
- 自动播放折叠/展开循环
- 单 HTML 文件，离线可用，无需构建

## 展开图布局

长方体展开为十字形展开图：

```
         +-------+
         |  顶面 |
         | a x b |
+--------+-------+--------+-------+
|  左面  |  前面 |  右面  |  后面 |
| b x c  | a x c | b x c  | a x c |
+--------+-------+--------+-------+
         |  底面 |
         | a x b |
         +-------+
```

## 技术栈

- [Three.js](https://threejs.org/) r162 -- 3D 渲染
- Canvas API -- 动态面纹理
- 纯 HTML / CSS / JS -- 无框架、无打包工具

## 使用方式

在浏览器中打开 `index.html` 即可，无需安装。

## 状态

已完成 -- 可用的单页应用。

## 许可证

MIT
