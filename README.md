<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=2F81F7&center=true&vCenter=true&width=620&lines=Edge+AI+that+actually+runs+on-device;%E7%AB%AF%E4%BE%A7%E8%AF%AD%E9%9F%B3%E5%8A%A9%E6%89%8B+%C2%B7+%E5%85%B7%E8%BA%AB%E6%99%BA%E8%83%BD+%C2%B7+MCP+%E6%9C%BA%E5%99%A8%E4%BA%BA;ESP32+%C2%B7+Orange+Pi+%C2%B7+Rust+%C2%B7+Python" alt="Typing SVG" />

**HBConline** · 边缘 AI 全栈：端侧语音助手、具身智能、MCP 机器人控制——从固件到 LLM 全链路自己搭。

</div>

## 🔭 Focus

- **全离线语音助手**：ESP32-S3 端侧唤醒（tflite）+ 香橙派边缘大脑（SenseVoice ASR / 两级决策 / Qwen3-0.6B / Matcha TTS）+ ESP8266 继电器执行，MQTT 端—边协同秒级闭环，全程局域网不走云
- **具身智能**：从 0 构建 VLA / OpenVLA / SmolVLA / Pi0；SO-ARM101 sim2sim（Isaac Lab → MuJoCo，双臂遥操作与真机标定）
- **MCP 机器人控制**：LLM 经 Model Context Protocol 把自然语言翻译成机械臂指令（DeepSeek + PySide6 GUI + 树莓派桥）
- **边缘 AI 应用**：OpenCV DNN 实时人员感知与推流网关、Tauri 桌面 AI 协作、把 263 页硬件手册编码成 Agent Skill

## 🧩 Featured Projects

| 项目 | 说明 | 技术 |
| --- | --- | --- |
| [xiaochen-voice](https://github.com/HBConline/xiaochen-voice) | 小宸同学：全离线家庭语音助手，唤醒→识别→决策→执行→播报端边闭环，含接线图 / BOM / GHCR 镜像 / 演示视频 | ESP32 · Orange Pi · Python |
| [every-embodied](https://github.com/HBConline/every-embodied) | 从 0 构建自己的具身智能机器人：VLA / OpenVLA / SmolVLA / Pi0 逐步深入 | Jupyter · VLA |
| [HLORO-AI](https://github.com/HBConline/HLORO-AI) | 基于 MCP 的工业机器人控制：自然语言直接驱动 HRB400 SCARA 机械臂 | Python · MCP · DeepSeek |
| [SmartGuard](https://github.com/HBConline/SmartGuard) | 边缘 AI 智能门卫：Qt5 + OpenCV DNN 实时人员感知，RTMP / MQTT 推流网关 | C++ · Qt5 · OpenCV |
| [hlink-desktop](https://github.com/HBConline/hlink-desktop) | 你和 AI 代理的私密协作空间，运行在自己电脑上 | Rust · Tauri · React |
| [orangepi4pro-skill](https://github.com/HBConline/orangepi4pro-skill) | 香橙派 4 Pro（A733）官方手册编码成 Claude Code Agent Skill，边缘设备直接编码部署 | Markdown · Agent Skill |

## 🚀 Highlights

- 🎬 [真机演示视频](https://b23.tv/lUWWbtx) — 小宸同学端到端语音全屋智能（bilibili）
- 🐳 [`ghcr.io/hbconline/xiaochen-voice-server`](https://github.com/users/HBConline/packages/container/package/xiaochen-voice-server) — linux/arm64 一键部署镜像
- 📦 [Releases](https://github.com/HBConline/xiaochen-voice/releases) — 固件 + 模型 + 接线文档五件套（附 md5）
- 🧪 全部仓库带独立测试套件，push 即跑 GitHub Actions

## 🛠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cplusplus,rust,jupyter,react,ts,flask,docker,linux,git,pytorch,nodejs&perline=12" alt="Tech stack" />
</p>

**端侧**：ESP32 · sherpa-onnx · SenseVoice · llama.cpp · MQTT　**AI**：Qwen3 · VLA · MCP · OpenCV　**桌面/前端**：Tauri · React · Qt5

## 🐍 Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/HBConline/HBConline/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/HBConline/HBConline/output/github-snake.svg" alt="Contribution snake" />
</picture>
