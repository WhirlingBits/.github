<div align="center">

# 🌀 WhirlingBits

**Professional ESP-IDF Components & IoT Solutions**

[![Website](https://img.shields.io/badge/Website-whirlingbits.de-blue?style=for-the-badge)](https://whirlingbits.de)
[![Documentation](https://img.shields.io/badge/Docs-docs.whirlingbits.de-green?style=for-the-badge)](https://docs.whirlingbits.de)

*Building reusable, well-documented ESP32 components for the embedded community*

</div>

---

## 🎯 What We Do

WhirlingBits develops **production-ready ESP-IDF components** with comprehensive documentation, examples, and best practices. Our mission is to accelerate ESP32 development by providing reliable, tested building blocks.

### 🔧 Core Principles

- ✅ **Well-Documented** - Doxygen API docs + Docusaurus guides
- ✅ **Thoroughly Tested** - Unit tests & hardware validation
- ✅ **Easy Integration** - CMake-based, follows ESP-IDF conventions
- ✅ **Community-Driven** - Open source, contributions welcome

---

## 📦 Component Library

### [wb-idf-core](https://github.com/WhirlingBits/wb-idf-core)

Collection of reusable ESP-IDF components for common peripherals and protocols.

#### Available Components

| Component | Description | Status | Documentation |
|-----------|-------------|--------|---------------|
| **[wb-idf-i2c](https://github.com/WhirlingBits/wb-idf-core/tree/main/wb-idf-i2c)** | I²C Master Driver with multi-instance support | ✅ Stable | [📖 API Docs](https://docs.whirlingbits.de/wb-idf-core/wb_idf_i2c) |
| **wb-idf-spi** | SPI Communication Handler | 🚧 In Development | Coming Soon |

#### Key Features

- 🔄 **Multi-Instance Support** - Run multiple peripherals simultaneously
- ⚙️ **Kconfig Integration** - Easy configuration via menuconfig
- 📚 **Rich Examples** - Complete working examples included
- 🧪 **Unit Tested** - ESP-IDF test framework integration
- 📖 **Doxygen Documentation** - Comprehensive API reference

#### Quick Start

```bash
# Add as ESP-IDF component
cd your-project/components
git clone https://github.com/WhirlingBits/wb-idf-core.git

# Or as Git submodule
git submodule add https://github.com/WhirlingBits/wb-idf-core.git components/wb-idf-core

# Configure via menuconfig
idf.py menuconfig
# Navigate to: Component config → WhirlingBits Components

# Build your project
idf.py build flash monitor
```

**[→ Full Documentation](https://docs.whirlingbits.de/wb-idf-core/)**



## 📚 Documentation Hub

### [docs.whirlingbits.de](https://docs.whirlingbits.de)

Unified documentation portal built with Docusaurus, featuring:

- 📖 **API Reference** - Auto-generated from Doxygen
- 🎓 **Tutorials** - Step-by-step guides
- 💡 **Examples** - Working code samples
- 🔧 **Configuration** - Kconfig options explained
- 🐛 **Troubleshooting** - Common issues & solutions

**Technology Stack:**
- [Docusaurus](https://docusaurus.io/) - Documentation framework
- [Doxygen](https://www.doxygen.nl/) - API documentation generator
- [GitHub Pages](https://pages.github.com/) - Hosting
- [GitHub Actions](https://github.com/features/actions) - CI/CD pipeline

---

## 🛠️ Development Stack

<div align="center">

![ESP-IDF](https://img.shields.io/badge/ESP--IDF-v5.x-000000?style=for-the-badge&logo=espressif)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Doxygen](https://img.shields.io/badge/Doxygen-2C4AA8?style=for-the-badge&logo=doxygen&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

</div>

---

## 🤝 Contributing

We welcome contributions from the community!

### How to Contribute

1. 🍴 **Fork** the repository
2. 🌿 **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. ✍️ **Commit** your changes (`git commit -m 'Add AmazingFeature'`)
4. 📤 **Push** to the branch (`git push origin feature/AmazingFeature`)
5. 🔀 **Open** a Pull Request

### Contribution Guidelines

- Follow [ESP-IDF style guide](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/contribute/style-guide.html)
- Add unit tests for new features
- Update documentation (Doxygen comments + guides)
- Run `idf.py clang-format` before committing

**[→ Contributing Guide](https://github.com/WhirlingBits/.github/blob/main/CONTRIBUTING.md)** | **[→ Code of Conduct](https://github.com/WhirlingBits/.github/blob/main/CODE_OF_CONDUCT.md)**

---

## 📖 Resources

### Learning Materials

- 📘 [ESP-IDF Programming Guide](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/)
- 🎥 [Component Development Tutorial](https://docs.whirlingbits.de/tutorials/component-development)
- 💡 [Best Practices](https://docs.whirlingbits.de/guides/best-practices)

### Component Templates

- 🏗️ [Component Template](https://github.com/WhirlingBits/wb-component-template) - Starter for new components
- 📝 [Documentation Template](https://github.com/WhirlingBits/wb-docs-template) - Doxygen + Docusaurus setup

---

## 🌟 Support Us

If you find our components useful:

- ⭐ **Star** our repositories
- 🐛 **Report bugs** and suggest features
- 🤝 **Contribute** code or documentation
- 📢 **Share** with the ESP32 community

---

## 📬 Contact

- 🌐 **Website:** [whirlingbits.de](https://whirlingbits.de)
- 📖 **Documentation:** [docs.whirlingbits.de](https://docs.whirlingbits.de)
- 📧 **Email:** [info@whirlingbits.de](mailto:info@whirlingbits.de)
- 💬 **Discussions:** [GitHub Discussions](https://github.com/orgs/WhirlingBits/discussions)
- 🐛 **Bug Reports:** [Issue Tracker](https://github.com/WhirlingBits/wb-idf-core/issues)
