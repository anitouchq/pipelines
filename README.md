# 🚀 Pipelines

## 📚 Список пайплайнов

| # | Язык / Стек | Что делает | Ссылка |
|---|-------------|------------|--------|
| 1 | 📦 **Node.js** | REST API, ESLint, Jest, Docker | [→](https://github.com/anitouchq/pipelines-nodejs) |
| 2 | 🐍 **Python** | flake8, pytest (matrix 3.9–3.12), Docker | [→](https://github.com/anitouchq/pipelines-python) |
| 3 | 🐹 **Go** | go vet, тесты с покрытием, Docker | [→](https://github.com/anitouchq/pipelines-go) |
| 4 | ⚙️ **C++** | CMake, Google Test, clang-format, Docker | [→](https://github.com/anitouchq/pipelines-cpp) |
| 5 | 🦀 **Rust (утилита)** | clippy, fmt, cargo test | [→](https://github.com/anitouchq/pipelines-rust) |
| 6 | 🐘 **PHP** | PHP lint, PHPUnit, Docker | [→](https://github.com/anitouchq/pipelines-php) |
| 7 | ☕ **Java** | Maven, JUnit 5, multi-stage Docker | [→](https://github.com/anitouchq/hello-java) |
| 8 | 🦀 **Rust (CI #1)** | clippy, fmt, cargo test, multi-stage Docker | [→](https://github.com/anitouchq/my-rust-app) |



## ⚙️ Что демонстрирует каждый пайплайн

| Язык | Lint | Test | Docker |
|------|------|------|--------|
| Node.js | ESLint | Jest | ✅ |
| Python | flake8 | pytest | ✅ |
| Go | go vet | go test | ✅ |
| C++ | clang-format | Google Test | ✅ |
| Rust (утилита) | clippy + fmt | cargo test | ✅ |
| PHP | php -l | PHPUnit | ✅ |
| Java | Maven | JUnit 5 | ✅ |
| Rust (CI #1) | clippy + fmt | cargo test | ✅ |


