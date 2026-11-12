# Development Templates

A collection of reusable project configurations, coding standards, and development guidelines for Python, C++, and MATLAB projects.

The goal of this repository is to maintain consistent coding practices, improve code quality, and simplify project setup across different programming languages.

## Repository Structure

```text
development-templates/
│
├── common/
│   ├── .editorconfig
│   └── .gitignore
│
├── python/
│   └── pyproject.toml
│
├── cpp/
│   └── .clang-format
│
├── matlab/
│   └── MATLAB_Style_Guide.md
│
├── README.md
└── .gitignore
```

## Coding Standards and Tools

### Python
- **Formatter:** Ruff
- **Linter:** Ruff
- **Configuration:** `pyproject.toml`
- **Standards:** Consistent formatting, import organization, naming conventions, and code quality checks.

### C++
- **Formatter:** clang-format
- **Linter:** clang-tidy
- **Configuration:** `.clang-format`
- **Standards:** Consistent indentation, brace placement, naming conventions, and code formatting.

### MATLAB
- **Code Analysis:** MATLAB Code Analyzer
- **Configuration:** MATLAB Editor settings
- **Standards:** Consistent naming conventions, indentation, documentation, and code organization.

## Common Configurations

Shared development configurations include:

- `.editorconfig` – Consistent editor settings across development environments.
- `.gitignore` – Excludes generated files, build artifacts, temporary files, and local development environments.

## Usage

These configurations can be copied into new projects to establish consistent development practices.

1. Select the configuration files relevant to your programming language.
2. Copy them into the root directory of your project.
3. Install the required development tools and VS Code extensions.
4. Follow the coding standards defined in the corresponding configuration files.

## Development Environment

Recommended editor: **Visual Studio Code**

The configurations are designed to work with VS Code and the corresponding language extensions and development tools.

## Languages and Technologies

- Python
- C++
- MATLAB
- Visual Studio Code
- Git and GitHub

---

*This repository is maintained as a reusable foundation for personal projects, coding practice, algorithm development, machine learning, and wireless communication research.*