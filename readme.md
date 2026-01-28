# 👋 Xin chào, tôi là NHH

<div align="center">
  
  ![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00F7F4&center=true&vCenter=true&width=600&lines=Data+Science+Student+%F0%9F%93%8A;Game+Developer+%F0%9F%8E%AE;Reverse+Engineer+%F0%9F%94%8D;3D+Graphics+Enthusiast+%F0%9F%8E%A8)
  
</div>

## 🚀 Giới thiệu
Tôi đang là sinh viên ngành **Khoa học Dữ liệu**, đam mê nghiên cứu và phát triển các ứng dụng AI, machine learning, game development và graphics programming. Luôn tìm kiếm cơ hội để học hỏi và áp dụng công nghệ vào giải quyết các vấn đề thực tế.

**Solo Developer** - Phát triển và maintain các dự án cá nhân từ ý tưởng đến implementation.

## 💼 Kỹ năng

### 🖥️ Ngôn ngữ lập trình chính
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)

### 🔧 Ngôn ngữ bổ sung
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

## 🔍 Chuyên môn đặc biệt

### 🛡️ Reverse Engineering
- 🔓 Dịch ngược phần mềm sử dụng **.NET Framework**
- 🎮 Phân tích và reverse các **game engine C++** thông dụng
- 🔧 Kinh nghiệm với công cụ debugging và decompilation

### 🎮 Game Development
- 🕹️ Thành thạo **Godot Engine** cho phát triển game 2D/3D
- 🎯 Đang học **Unity** để mở rộng kỹ năng game development
- 🖼️ Kinh nghiệm với **OpenGL** và **Vulkan** cho rendering 3D

### ⚡ High Performance Computing
- 🚀 NVIDIA CUDA programming cho tính toán song song
- 💻 Tối ưu hóa hiệu năng cho ứng dụng graphics và data processing

## 📊 GitHub Stats

<div align="center">
  
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=server-mode&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&include_all_commits=true&count_private=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=server-mode&theme=tokyonight&hide_border=true&background=0D1117)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=server-mode&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&langs_count=8)

</div>

## 🏆 Dự án nổi bật

### 🤖 [AiMimic – Continual Learning Toolkit](https://github.com/server-mode/AiMimic)
**⏱️ Development Time: 6 tháng | 👤 Solo Project**

Continual Learning Toolkit nhỏ gọn viết bằng PyTorch, tập trung vào nghiên cứu **Catastrophic Forgetting** và các chiến lược **Continual Learning** cho sequential tasks.

**Kỹ thuật triển khai:**
- 🧠 **Memory-based learning mechanism** - Implement Rehearsal strategy với MemoryBuffer cho replay mechanism (long-term retention)
- 🔄 **EWC (Elastic Weight Consolidation)** - Fisher Information Matrix để penalty các tham số quan trọng, ngăn chặn catastrophic forgetting
- ⚡ **Parameter Isolation với LoRA** - Low-rank adaptation cho linear layers, freeze backbone và chỉ train adapter per task
- 📊 **Metrics & Visualization** - AccuracyMatrix (task performance tracking), ForgettingMetric (max acc - current acc), heatmap visualization
- 🎯 **Multi-strategy Trainer** - Unified ContinualTrainer hỗ trợ naive/rehearsal/ewc strategies với YAML config

**Key Features:**
- Sequential task training (MNIST/CIFAR splits)
- Forgetting score measurement & visualization
- Fisher diagonal approximation for EWC
- Memory replay buffer với capacity management

**Tech Stack:** 

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) 
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

---

### 🚀 [PyLittle – Hardware-Aware LLM Inference](https://github.com/server-mode/PyLittle)
**⏱️ Development Time: 10 tháng | 👤 Solo Project**

Thư viện LLM inference được thiết kế cho hardware resource-constrained, tối ưu hóa để chạy các mô hình lớn trên máy có VRAM thấp (6-8GB) với hiệu suất gần GPU-class.

**Kỹ thuật triển khai:**
- 💾 **Low-VRAM first design** - Quantized weights (Q4/Q8) và KV-cache quantization để giảm memory footprint, hierarchical offload (VRAM ↔ pinned RAM ↔ disk mmap) với async prefetch và LRU eviction
- 🔧 **Multi-backend architecture** - Pluggable backends hỗ trợ CPU, CUDA (NVIDIA), ROCm (AMD), Vulkan (cross-vendor) với fused kernels roadmap
- 🛡️ **Safety & durability** - Thermal/usage monitoring (NVML/ROCm SMI), policy-based throttling để bảo vệ hardware yếu, graceful degrade với auto-reduce batch/context/precision
- 🔄 **Memory budgeter** - Đọc device capabilities và tự động plan allocation (weights/KV/scratch) để fit best trên weak GPUs
- 🐍 **Python-first API** - Clean API tương thích NumPy/Torch, HF adapters integration, optional native engine via pybind11

**Key Features:**
- Safetensors-first loading với bitsandbytes 4/8-bit quantization
- Device auto-mapping với max_memory budget
- Benchmark harness để compare với vanilla HF
- CLI interface và thermal safety policies

**Tech Stack:** 

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/-CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

---

<div align="center">
  
### 🎯 Đang làm việc với
  
🔹 Dự án thực tế với **Supabase** cho backend scalable  
🔹 Học **AWS** để deploy và quản lý cloud infrastructure  
🔹 Phát triển game với **Godot** và **Unity**  
🔹 Nghiên cứu AI và data science applications  

</div>

## 📫 Liên hệ

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
