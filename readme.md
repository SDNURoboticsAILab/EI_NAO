# NAO Embodied Intelligence Development Framework

## 简介

NAO Robot Embodied Intelligence Development Framework 是一个基于qi3为NAO机器人开发智能应用的框架。该框架旨在提供一套易于使用的工具和库，帮助开发者快速构建和部署基于NAO的智能系统。可以基于此系统快速部署相关的

## 特性

- **模块化设计**：框架采用模块化设计，便于扩展和维护。
- **多语言支持**：支持Python和C++，让开发者可以使用自己熟悉的语言进行开发。
- **易于集成**：提供丰富的API，方便与其他系统和服务集成。
- **实时反馈**：支持实时数据处理和反馈，提升用户交互体验。

## 安装

### 环境要求

#### Linux

Ubuntu 18.04+
Python-venv 3.8+

#### MacOS

Python3.8+
Conan

Note:需要使用Conan源码编译libqi-python的库

#### Windows

Windows环境源码编译libqi失败，暂未找到解决方法

### 依赖

克隆本仓库：

```bash
git clone https://github.com/SDNURoboticsAILab/EI_NAO.git
# or
git clone git@github.com:SDNURoboticsAILab/EI_NAO.git
```

安装依赖：

```bash
cd your_workfolder
python3 -m venv my-venv 
source ./my-venv/bin/activate
pip install -r requirements.txt
# MacOS需要源码编译qi-python的库
```

## 开发流程

在进行此项目开发时，遵循以下开发流程：

### 1. 需求分析

- **目标定义**：确定项目的目标和需求，明确NAO机器人需要执行的任务。

### 2. 设计阶段

- **系统架构设计**：设计整体系统架构，包括软件组件、模块和接口，需要详细的画出系统架构图。
- **详细设计**：对每个模块进行详细设计，包括数据结构、算法和流程图，需要详细的画出系统架构图。

### 3. 开发阶段

- **环境搭建**：设置开发环境，包括必要的软件、工具和库。
- **开发**：根据之前的设计架构完成相关的代码。
- **github仓库**：开发使用提交Pull Request的方式，commit使用AngularJS规范，如果有功能上的修改，请fork仓库后进行Pull Request。

### 4. 测试阶段

- **单元测试**：对每个模块进行单元测试，确保功能正常。
- **集成测试**：将各个模块进行集成，测试系统整体功能。

### 5. 部署阶段

- **部署准备**：准备部署文档和用户手册。
- **实际部署**：将软件部署到NAO机器人上，进行现场测试。
- **文档整理**：整理项目文档，包括设计文档、用户手册和开发文档。

### 6. 维护阶段

- **监控与支持**：进行软件运行监控，提供技术支持。
- **更新与迭代**：根据用户反馈和需求变化，定期更新软件，修复bug和添加新功能。
