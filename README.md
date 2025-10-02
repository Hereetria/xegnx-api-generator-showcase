# ⚡ Xegnx API Generator Showcase — Next-Level API Generator

<br>

[![Report Bug](https://img.shields.io/badge/🐛_Report_Bug-red?style=for-the-badge)](../../issues/new?labels=bug)
[![Request Feature](https://img.shields.io/badge/✨_Request_Feature-blue?style=for-the-badge)](../../issues/new?labels=enhancement)

<br>

## 📌 Project Overview

**Xegnx API Generator** is a powerful internal tool that generates **clean, production-ready .NET REST APIs** in seconds. Currently, it focuses on generating **.NET-based APIs**, but the long-term goal is to support **multiple technologies and architectures** beyond .NET.

<br>

By providing structured **input folders** (especially the `Entities` folder), **output paths**, and **project patterns**, it automatically creates the entire backend structure — from repositories to controllers — following the **Repository Design Pattern** and clean code principles.

<br>

During the **project generation process**, the **Builder Design Pattern** is used to construct projects step by step in a flexible and maintainable way.

> This repository serves as a **showcase** for the tool’s capabilities. The actual source code is **not shared**, but its usage has already accelerated development in real projects like [**social-media-api-prototype**](https://github.com/Hereetria/social-media-api-prototype) and [**xeno-terra-api**](https://github.com/Hereetria/xeno-terra-api), where the entire API foundations were scaffolded with this generator.

<br>

## ✨ Features

- 🧠 **Entity-based Input** — Simply point to your `Entities` folder to define your data models  
- 🗂️ **Pattern-Aware Generation** — Configure folder paths and naming conventions to match your architecture  
- ⚙️ **.NET REST API Output** — Generates repository, service, and controller layers automatically  
- 🧱 **Repository Design Pattern** — All generated code follows a layered, maintainable structure  
- 🧼 **Clean Code** — Output adheres to best practices, enabling fast development without sacrificing quality  
- 🔧 **Auto DI Configuration** — Any new service is automatically registered in the dependency injection container  
- 🚀 **Development Accelerator** — Eliminates repetitive setup work and speeds up new project bootstrapping

<br>

## 🖼️ Screenshots
Shown below in order:  
**1. Inputs**

<p align="center">
  <img src="./docs/screenshots/inputs.png" width="32%">
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/ce/Transparent.gif" width="32%">
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/ce/Transparent.gif" width="32%">
</p>

<br>

## 🧰 Tech Stack

<p>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C# Badge" height="32" />
  <img src="https://img.shields.io/badge/.NET_8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET 8 Badge" height="32" />
  <img src="https://img.shields.io/badge/Windows_Forms-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows Forms Badge" height="32" />
</p>



<br>

## 📜 License

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

This project is licensed under the terms described in the [LICENSE](./LICENSE) file.

---

© 2025 Yusuf Okan Sirkeci — [Hereetria](https://github.com/Hereetria)
