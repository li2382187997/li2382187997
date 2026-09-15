# 李雅洁 / Li Yajie

**通信工程 本科在读（2023 级）· 淮南师范学院 · 求职方向：AI Agent / 应用开发**

安徽淮南 · 邮箱 2382187997@qq.com

---

## 关于我 / About

通信工程背景，主业方向是 **AI Agent 与应用开发**。习惯用 AI 工具链把想法快速做成能跑起来的东西，而不是停留在方案里。

现阶段的技术积累分布在三层：

- **应用层** —— 原生 Web 应用（HTML / CSS / JS），能独立完成需求定义到上线
- **系统与嵌入式层** —— C/C++，STM32 与嵌入式 Linux，接触过驱动、串口协议、像素级 UI
- **自动化层** —— Python 脚本，把重复劳动沉淀成可复用工具

学业情况：**GPA 3.91 / 4.5（专业前 5%）**，核心课程平均绩点 4.11。曾获国家励志奖学金、优秀学生标兵、一等/二等奖学金。

---

## 技术栈 / Tech

| 分类 | 内容 |
| --- | --- |
| 编程语言 | C / C++、Python、HTML / CSS / JavaScript |
| 嵌入式 | STM32（外设驱动、IIC/USART）、嵌入式 Linux（帧缓冲、socket、poll I/O 复用） |
| 数据与存储 | IndexedDB、localStorage、JSON 备份与恢复 |
| AI 工具链 | Codex、WorkBuddy、Obsidian、gzh-design、妙搭 |
| 其他 | Git、Linux 常用命令 |

证书：CET-4、全国计算机等级考试一级。

---

## 项目 / Projects

### [paint-workbench](https://github.com/li2382187997/paint-workbench)
**零依赖单文件绘画工作台 · 原生 JavaScript**

为自己每天的板绘练习做的一款管理工具，全部功能装在一个 HTML 文件里，**无任何外部依赖**。

- 计时打卡（开始 / 暂停 / 继续 / 结束保存）
- 近 7 天练习时长趋势图（纯 DOM 自绘柱状图，未使用图表库）
- 拖拽上传与 Ctrl+V 粘贴上传，作品分组展示
- IndexedDB 三张表持久化，支持 JSON 备份导出与导入
- 深浅色三档主题，图片缩放查看

在线体验：[Demo](https://024bb0c4d8d64695b7f852cf63aec87b.app.workbuddy.host)

### [linux-smart-home](https://github.com/li2382187997/linux-smart-home)
**嵌入式 Linux 智能家居控制终端 · C**

学校企业实训期间独立完成的项目，基于 ARM 嵌入式 Linux 板 + STM32 从机 + Ubuntu 语音识别服务器（TCP）三层结构。

- 不依赖 Qt/GTK，按像素直接写入 ARGB 完成界面自绘
- 自写 24 位 BMP 解码器（自解文件头、行对齐、Y 轴翻转、BGR→ARGB 转换）
- 语音控制、电子相册、留言器录音播放、灯光控制四个功能模块
- 触摸去抖处理，串口 poll 轮询与超时重试

---

## 其他 / More

- **AI 工具落地**：实习期间自建可复用 Skill 与工作流（面试准备、Obsidian 知识库），把重复性工作沉淀为脚本资产
- **竞赛**：第十五届"北斗杯"省级二等奖 —— 提出北斗导航用于交通事故预警的构想并完成建模与答辩
- **作品集**：[飞书个人作品集](https://my.feishu.cn/page/PsKemRyMXd7dBBa4MupcB5IDnxh)

---

> 本项目以外的技术活动与实践记录，可以在上方两个仓库的提交历史里看到。欢迎交流：2382187997@qq.com
