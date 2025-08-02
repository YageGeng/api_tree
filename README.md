# api_tree

**api_tree** is a language-agnostic tool that leverages [tree-sitter](https://tree-sitter.github.io/) to parse source code and automatically extract structured API documentation. It is designed for extensibility, with first-class support for Rust and plans to support more programming languages in the future.

---

## Features

- 🌳 **Tree-sitter Powered**: Uses the powerful incremental parsing capabilities of tree-sitter to accurately analyze source code.
- 🦀 **Rust First**: Out-of-the-box support for Rust API extraction.
- 🌐 **Multi-language Ready**: Easily extendable to support other programming languages (e.g., Python, Go, Java).
- 📝 **Structured Output**: Generates machine-readable, structured API documentation (e.g., JSON, YAML) suitable for AI use cases.
- ⚡ **Easy Integration**: CLI and/or API interface for seamless integration into your workflow.

---

## Use Cases

- Generate up-to-date API documentation for your codebase.
- Feed API structures to AI models for code understanding, code search, or code generation.
- Enable multilingual codebase documentation in a unified format.
- Automate documentation processes in CI/CD pipelines.

---

## Quick Start

1. **Clone the Repository**
   ```sh
   git clone https://github.com/YageGeng/api_tree.git
   cd api_tree
   ```

2. **Build or Install**
   - (Instructions to build or install the tool, e.g., using Cargo, pip, npm, etc., depending on your implementation.)

3. **Extract API Documentation**
   ```sh
   api_tree extract --language rust --output api.json path/to/your/src
   ```

4. **(Optional) Extend for Other Languages**
   - See the [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on adding new language support.

---

## Roadmap

- [x] Rust language support
- [ ] CLI usage examples and documentation
- [ ] Support for more programming languages (Python, Go, Java, etc.)
- [ ] Web/API service interface
- [ ] Advanced filtering and custom output formats

---

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

---

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## Acknowledgements

- [tree-sitter](https://tree-sitter.github.io/) for powerful, language-agnostic parsing.
- Inspiration from open-source API documentation tools and the developer community.

---

**api_tree**: Build a unified, AI-friendly API documentation pipeline for your codebase!
