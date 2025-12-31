> [!NOTE]
> This project is a fork of [luxonis/depthai](https://github.com/luxonis/depthai). The original project and its contributors can be found there.

# DepthAI API Demo Program

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![CI/CD Status](https://github.com/wesship/depthai/actions/workflows/ci.yml/badge.svg)](https://github.com/wesship/depthai/actions/workflows/ci.yml)

> This repository contains a demo application for the DepthAI API, which can be used to load different networks, create pipelines, record video, and more.

---

## ✨ Features

- **Run AI Models**: Supports a variety of pre-trained models for tasks like object detection, pose estimation, and segmentation.
- **Create Custom Pipelines**: Build and run your own custom DepthAI pipelines.
- **Record Video**: Record and save video streams from the device.
- **Interactive GUI**: A user-friendly QT interface for exploring DepthAI features.

---

## 🚀 Getting Started

### Prerequisites

- A Luxonis OAK camera

### Installation

1. Clone the repository:
   ```bash
   git clone --recursive https://github.com/wesship/depthai.git
   cd depthai
   ```
2. Install OS dependencies:
   ```bash
   sudo curl -fL https://docs.luxonis.com/install_dependencies.sh | bash
   ```
3. Install Python dependencies:
   ```bash
   python3 install_requirements.py
   ```

### Usage

```bash
python3 depthai_demo.py -gt cv
```

---

## 🛠️ Built With

- [Python](https://www.python.org/)
- [OpenCV](https://opencv.org/)
- [Qt](https://www.qt.io/)

---

## 🤝 Contributing

Contributions are welcome! Please see the [contributing guidelines](CONTRIBUTING.md) for more information.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
