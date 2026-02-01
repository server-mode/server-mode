# 👋 Hi, I'm NHH

<div align="center">
  
  ![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00F7F4&center=true&vCenter=true&width=600&lines=Data+Science+Student+%F0%9F%93%8A;Game+Developer+%F0%9F%8E%AE;Reverse+Engineer+%F0%9F%94%8D;3D+Graphics+Enthusiast+%F0%9F%8E%A8)
  
</div>

## 🚀 About Me
Currently a **Data Science** student, researching and developing AI applications, machine learning, game development, and graphics programming. Always looking for opportunities to learn and apply technology to solve real-world problems.

**Solo Developer** - Building and maintaining personal projects from concept to implementation.

## 💼 Skills

### 🖥️ Primary Languages
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)

### 🔧 Additional Languages
![C++](https://img.shields.io/badge/-C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/-C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CUDA](https://img.shields.io/badge/-CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

### 🎨 Graphics & Game Development
![OpenGL](https://img.shields.io/badge/-OpenGL-5586A4?style=for-the-badge&logo=opengl&logoColor=white)
![Vulkan](https://img.shields.io/badge/-Vulkan-AC162C?style=for-the-badge&logo=vulkan&logoColor=white)
![Three.js](https://img.shields.io/badge/-Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![Godot](https://img.shields.io/badge/-Godot-478CBF?style=for-the-badge&logo=godot-engine&logoColor=white)
![Unity](https://img.shields.io/badge/-Unity-000000?style=for-the-badge&logo=unity&logoColor=white)

### 🌐 Web Frameworks & Technologies
![React](https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![.NET](https://img.shields.io/badge/-.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

### 🗄️ Database & Cloud
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

## 🔍 Specialized Expertise

### 🛡️ Reverse Engineering
- 🔓 Reverse engineering software using **.NET Framework**
- 🎮 Analyzing and reversing common **C++ game engines**
- 🔧 Experience with debugging and decompilation tools

### 🎮 Game Development
- 🕹️ Proficient in **Godot Engine** for 2D/3D game development
- 🎯 Learning **Unity** to expand game development skills
- 🖼️ Experience with **OpenGL** and **Vulkan** for 3D rendering

### ⚡ High Performance Computing
- 🚀 NVIDIA CUDA programming for parallel computing
- 💻 Performance optimization for graphics and data processing applications

## 📊 GitHub Stats

<div align="center">
  
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=server-mode&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&include_all_commits=true&count_private=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=server-mode&theme=tokyonight&hide_border=true&background=0D1117)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=server-mode&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&langs_count=8)

</div>

## 🏆 Featured Projects

### 🤖 [AiMimic – Continual Learning Toolkit](https://github.com/server-mode/AiMimic)
**⏱️ Development Time: 6 months | 👤 Solo Project**

A compact Continual Learning Toolkit written in PyTorch, focusing on **Catastrophic Forgetting** research and **Continual Learning** strategies for sequential tasks.

**Technical Implementation:**
- 🧠 **Memory-based learning mechanism** - Implemented Rehearsal strategy with MemoryBuffer for replay mechanism (long-term retention)
- 🔄 **EWC (Elastic Weight Consolidation)** - Fisher Information Matrix to penalize important parameters, preventing catastrophic forgetting
- ⚡ **Parameter Isolation with LoRA** - Low-rank adaptation for linear layers, freeze backbone and train only adapter per task
- 📊 **Metrics & Visualization** - AccuracyMatrix (task performance tracking), ForgettingMetric (max acc - current acc), heatmap visualization
- 🎯 **Multi-strategy Trainer** - Unified ContinualTrainer supporting naive/rehearsal/ewc strategies with YAML config

**Key Features:**
- Sequential task training (MNIST/CIFAR splits)
- Forgetting score measurement & visualization
- Fisher diagonal approximation for EWC
- Memory replay buffer with capacity management

**Tech Stack:** 

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) 
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

---

### 🚀 [PyLittle – Hardware-Aware LLM Inference](https://github.com/server-mode/PyLittle)
**⏱️ Development Time: 10 months | 👤 Solo Project**

An LLM inference library designed for resource-constrained hardware, optimized to run large models on machines with low VRAM (6-8GB) at near GPU-class performance.

**Technical Implementation:**
- 💾 **Low-VRAM first design** - Quantized weights (Q4/Q8) and KV-cache quantization to reduce memory footprint, hierarchical offload (VRAM ↔ pinned RAM ↔ disk mmap) with async prefetch and LRU eviction
- 🔧 **Multi-backend architecture** - Pluggable backends supporting CPU, CUDA (NVIDIA), ROCm (AMD), Vulkan (cross-vendor) with fused kernels roadmap
- 🛡️ **Safety & durability** - Thermal/usage monitoring (NVML/ROCm SMI), policy-based throttling to protect weak hardware, graceful degrade with auto-reduce batch/context/precision
- 🔄 **Memory budgeter** - Reads device capabilities and automatically plans allocation (weights/KV/scratch) to best fit on weak GPUs
- 🐍 **Python-first API** - Clean API compatible with NumPy/Torch, HF adapters integration, optional native engine via pybind11

**Key Features:**
- Safetensors-first loading with bitsandbytes 4/8-bit quantization
- Device auto-mapping with max_memory budget
- Benchmark harness to compare with vanilla HF
- CLI interface and thermal safety policies

**Tech Stack:** 

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/-CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

---

<div align="center">
  
### 🎯 Currently Working On
  
🔹 Real-world projects with **Supabase** for scalable backend  
🔹 Learning **AWS** for deployment and cloud infrastructure management  
🔹 Game development with **Godot** and **Unity**  
🔹 AI and data science applications research  

</div>

## 📫 Contact

<div align="center">

[![Email](https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Kkeo052524@gmail.com)
[![Facebook](https://img.shields.io/badge/-Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/server-mode)

📧 **Kkeo052524@gmail.com**  
📘 **Facebook:** *Update soon*

</div>

## 📈 Profile Views

<div align="center">
  
![](https://komarev.com/ghpvc/?username=server-mode&color=blueviolet&style=for-the-badge)

</div>

---

<div align="center">

**🎮 Game Dev | 🔍 Reverse Engineer | 📊 Data Scientist | 🎨 Graphics Programmer**

</div>

---

<div align="center">
⭐️ From [server-mode](https://github.com/server-mode)
</div>
