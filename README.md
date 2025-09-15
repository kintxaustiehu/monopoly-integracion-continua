# Monopoly Continuous Integration

This repository is devoted to adding **Continuous Integration (CI)** into an existing Monopoly project.

---

## 🚀 Purpose

The main goal of this project is to integrate automated building, testing, and code quality checks into an existing Monopoly codebase. This ensures that changes are validated reliably before merging.

---

## 📂 Structure

- `.github/workflows/` — workflow definitions for CI (GitHub Actions)  
- `src/` — Java source code of Monopoly  
- `pom.xml` — Maven project descriptor  
- `sonar-project.properties` — configuration for SonarQube (code quality / static analysis)  
- Project settings files (e.g. `.settings/`, `.classpath`, `.project`)  

---

## 🔧 What is being integrated

- **Automated build and test runs** on push / pull request  
- **Static code analysis** (via SonarQube) to detect code smells, bugs, or vulnerabilities  
- Checks that fail early if quality thresholds are not met  
- Possible code coverage, style or formatting checks (depending on configuration)  

---

## 🛠 How to use / contribute

1. Clone the repository:

   ```bash
   git clone https://github.com/kintxaustiehu/monopoly-integracion-continua.git
