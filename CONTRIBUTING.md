# Contributing to WhirlingBits

Thank you for your interest in contributing! 🎉

## 🚀 Quick Start

```bash
# Fork & clone
git clone https://github.com/YOUR_USERNAME/wb-idf-core.git
cd wb-idf-core

# Set up ESP-IDF
. $IDF_PATH/export.sh

# Create feature branch
git checkout -b feature/my-feature

# Make changes, test, commit
git add .
git commit -m "feat: add my feature"

# Push & create PR
git push origin feature/my-feature
```

## 📋 Guidelines

### Code Style
- Follow [ESP-IDF C Style Guide](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/contribute/style-guide.html)
- Run `idf.py clang-format` before committing
- Use meaningful commit messages ([Conventional Commits](https://www.conventionalcommits.org/))

### Documentation
- Add Doxygen comments for all public APIs
- Update README.md if adding features
- Include usage examples

### Testing
- Add unit tests for new features
- Ensure all existing tests pass
- Test on real hardware if possible

## 🔄 Pull Request Process

1. Update documentation
2. Add/update tests
3. Ensure CI passes
4. Request review from maintainers
5. Address review comments

## 🐛 Reporting Bugs

Use [Bug Report Template](https://github.com/WhirlingBits/wb-idf-core/issues/new?template=bug_report.md)

## 💡 Feature Requests

Use [Feature Request Template](https://github.com/WhirlingBits/wb-idf-core/issues/new?template=feature_request.md)

## 📬 Questions?

- 💬 [GitHub Discussions](https://github.com/orgs/WhirlingBits/discussions)
- 📧 Email: info@whirlingbits.de

## 📄 License

By contributing, you agree that your contributions will be licensed under the MIT License.