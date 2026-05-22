# 初中物理笔记 (Junior High School Physics Notes)

**物理学**：研究物质结构、相互作用、运动规律的科学。

本项目是将一份详尽的初中物理核心知识点与定量实验笔记，整理并组织而成的 GitBook 电子书。内容涵盖了从基础的测量与单位，到力学、热学、电磁学、光学、声学，乃至现代量子力学的初步知识。

---

## 🌟 特点 (Key Features)

* **模块化章节**：摆脱了单一超长文档，将所有核心主题拆分为独立的章节，更加利于阅读和按专题检索。
* **LaTeX 公式支持**：内置 KaTeX 插件，全方位精准渲染各种复杂的物理和数学公式（如胡克定律、电学保护电路计算、麦克斯韦方程组相关的电磁感应公式等）。
* **自动化部署**：集成了 GitHub Actions 工作流，每次将修改推送到主分支时都会自动构建并更新 GitHub Pages 页面。
* **本地热重载**：基于 HonKit 构建，支持在本地启动开发服务器，实现修改即时预览。

---

## 📚 目录 (Table of Contents)

* [一、 测量、基本单位与物理恒量](chapters/01_measurement.md) — 长度与时间测量细节、卡尺/千分尺原理及物理常数对照大表
* [二、 运动学 (Kinematics)](chapters/02_kinematics.md) — 匀变速直线运动、平抛运动、圆周运动、简谐振动公式群
* [三、 力学 (Mechanics)](chapters/03_mechanics.md) — 弹力（并/串联弹簧定量推导）、摩擦力及牛顿三大运动定律
* [四、 机械能、动量与功 (Energy & Momentum)](chapters/04_energy_momentum.md) — 动能定理、动量守恒及弹性/非弹性碰撞定量推导
* [五、 质量、密度与流体压强 (Matter & Pressure)](chapters/05_matter_pressure.md) — 大气压强、连通器、经典气体实验三大定律（玻意耳、查理、盖-吕萨克）
* [六、 机械传动机构与简单机械 (Simple Machines)](chapters/06_simple_machines.md) — 差动滑轮（神仙葫芦）原理、滑轮组、斜面与轮轴
* [七、 声学 (Acoustics)](chapters/07_acoustics.md) — 声音产生与传播、音调/响度分析、振动图像与波动图像对比
* [八、 光学 (Optics)](chapters/08_optics.md) — 光的反射/折射与全反射、凸透镜成像规律及物体-光屏最小距离深度推导
* [九、 热学与分子动理论 (Thermodynamics)](chapters/09_thermodynamics.md) — 物态变化、分子动理论、内能、热力学四大定律
* [十、 电学、电路与定量实验 (Electricity)](chapters/10_electricity.md) — 欧姆定律、电表改装、伏安法/伏阻法/安阻法/替代法/电桥法/欧姆表法等电学实验全方位总结
* [十一、 磁学与电磁感应 (Magnetism)](chapters/11_magnetism.md) — 安培力与洛伦兹力、法拉第电磁感应定律、理想变压器公式及交流电
* [十二、 量子力学初步 (Quantum Mechanics)](chapters/12_quantum_mechanics.md) — 量子物理的基础常识与初步概念

---

## 🛠️ 本地运行与开发 (Local Development)

如果你想在本地预览这本电子书，需要确保系统中已安装 [Node.js](https://nodejs.org/)。

### 1. 安装依赖
克隆项目后，在根目录下运行以下命令安装 HonKit 和 KaTeX 依赖：
```bash
npm install
```

### 2. 本地预览 (Hot-reload)
启动本地服务：
```bash
npm run dev
```
启动后在浏览器中打开 `http://localhost:4000` 即可实时阅读并预览修改。

### 3. 生成静态网站
如果你需要手动构建静态 HTML 网页：
```bash
npm run build
```
生成的网页文件会保存在根目录下的 `_book/` 文件夹中。

---

## 🌐 网页在线查看 (Online Reading)

你可以直接在浏览器中打开以下网址在线阅读本书：

👉 **[初中物理笔记在线阅读](https://yvonshong.github.io/Junior_High_School_Physics_Note/)**

---

## 📄 开源协议 (License)

本项目采用 [MIT License](LICENSE) 协议开源。
