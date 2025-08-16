# 🚀 Broke CLI - Ultimate Coding Assistant

> **The most powerful CLI coding assistant**  
> *Code, fix, debug, and create with AI at your fingertips*

[![Version](https://img.shields.io/badge/version-1.0.2-blue.svg)](https://github.com/broke-cli/broke-cli)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Node](https://img.shields.io/badge/node-%3E%3D18.0.0-brightgreen.svg)](https://nodejs.org/)

## 📑 Table of Contents

- [Features](#-features)
- [Quick Start](#-quick-start)
- [Available Commands](#-available-commands)
- [Auto-Analyze Command](#-auto-analyze-command)
- [Examples](#-examples)
- [How It Works](#-how-it-works)
- [Troubleshooting](#-troubleshooting)
- [Try It Out](#-try-it-out)
- [Documentation](#-documentation)
- [Contributing](#-contributing)
- [License](#-license)

## ✨ Features

- 🎯 **Smart Code Analysis** - Analyze and understand your codebase
- 🔧 **Auto-Fix** - Automatically fix bugs and issues
- 📝 **Code Generation** - Generate code from natural language descriptions
- 🐛 **Debug Assistant** - Get help debugging complex issues
- 🎨 **Beautiful Terminal UI** - Rich colors, animations, and modern design
- 📊 **Real-time Logs** - Colored, structured logging with multiple levels
- 🌐 **AI Integration** - Lightning-fast AI responses
- 📁 **File Context** - Understand your project structure
- 🔍 **Smart Search** - Find and analyze code patterns
- 📚 **Documentation** - Generate and improve documentation
- 🤖 **Auto-Analysis** - Automatically detect and analyze existing project structures
- 🔄 **Smart Updates** - Intelligently update existing files while maintaining compatibility
- 🎯 **Project Detection** - Auto-detect project types, frameworks, and dependencies
- 📋 **Intelligent Suggestions** - Provide context-aware suggestions for improvements

## 🚀 Quick Start

### Prerequisites
- Node.js 18.0.0 or higher
- npm or yarn package manager

### Installation

```bash
# Install globally
npm install -g broke-cli

# Verify installation
broke --version
```

### First Time Setup

```bash
# No setup required! Just install and start using
# The CLI comes pre-configured with our API key
# No configuration files or API keys needed
```

### Basic Usage

```bash
# Start with interactive mode
broke

# Quick project overview
broke auto-analyze --summary

# Generate code
broke generate "Create a React component"

# Analyze existing code
broke analyze src/main.js
```

## 📋 Available Commands

### 🔍 Analysis Commands
- **`broke analyze <file>`** - Analyze and review specific files
- **`broke auto-analyze`** - Automatically analyze entire directory
- **`broke auto-analyze --summary`** - Quick project overview
- **`broke auto-analyze --update`** - Auto-update existing files
- **`broke auto-analyze --interactive`** - Selective file updates
- **`broke auto-analyze --fix`** - Auto-fix common issues
- **`broke auto-analyze --create`** - Create missing essential files

### 🚀 Generation Commands
- **`broke generate <description>`** - Generate code from description
- **`broke generate <description> --project`** - Generate complete project
- **`broke generate <description> --multiple`** - Generate multiple files
- **`broke generate <description> --interactive`** - Interactive generation

### 🛠️ Fix & Debug Commands
- **`broke fix <issue>`** - Fix specific issues in code
- **`broke debug <problem>`** - Get debugging help
- **`broke edit <file>`** - Edit files with AI assistance
- **`broke edit-dir <directory>`** - Edit entire directories

### 📊 Utility Commands
- **`broke logs`** - View command logs

### 📝 Utility Commands
- **`broke prompt <text>`** - Direct AI prompt
- **`broke help`** - Show help information
- **`broke version`** - Show version information

## 🔍 Auto-Analyze Command

The new `auto-analyze` command automatically detects and analyzes your existing project structure:

```bash
# Quick overview of your project
broke auto-analyze --summary

# Auto-update existing files with improvements
broke auto-analyze --update

# Interactive mode for selective updates
broke auto-analyze --interactive

# Auto-fix common issues
broke auto-analyze --fix

# Create missing essential files
broke auto-analyze --create
```

### What it does:
- 🔍 **Project Detection**: Automatically identifies project type (React, Vue, Python, Java, etc.)
- 📊 **Dependency Analysis**: Extracts and analyzes dependencies from package.json, requirements.txt, etc.
- 🏗️ **Framework Recognition**: Detects frameworks and libraries in use
- 💡 **Smart Suggestions**: Provides context-aware improvement suggestions
- 🔄 **Intelligent Updates**: Suggests and applies improvements while maintaining compatibility
- 📝 **File Generation**: Creates missing essential files (README, .gitignore, etc.)

## 💡 Examples

### Analyze Existing Project
```bash
# Quick overview
broke auto-analyze --summary

# Full analysis with suggestions
broke auto-analyze

# Auto-fix common issues
broke auto-analyze --fix
```

### Generate New Code
```bash
# Simple component
broke generate "Create a React button component"

# Complete project
broke generate "Build a REST API with Express" --project

# Multiple files
broke generate "Create a user authentication system" --multiple
```

### Fix Issues
```bash
# Fix specific problem
broke fix "Fix the authentication bug in login.js"

# Debug issue
broke debug "Why is my API returning 500 errors?"

# Edit file with AI
broke edit src/components/Header.js
```

## 🔧 How It Works

The CLI is pre-configured with our API key, so you can start using it immediately after installation. No configuration files or API keys needed!

## 🚨 Troubleshooting

### Common Issues

**"Command not found"**
```bash
# Reinstall globally
npm uninstall -g broke-cli
npm install -g broke-cli

# Or use npx
npx broke-cli --version```

# Or use npx
npx broke-cli --version
```

**"Permission denied"**
```bash
# On Unix systems, you might need sudo
sudo npm install -g broke-cli

# Or use nvm to avoid permission issues
nvm install node
nvm use node
npm install -g broke-cli
```

### Getting Help

- Run `broke help` for command overview
- Check logs with `broke logs`
- Visit our [GitHub Issues](https://github.com/RifatArefinBD/broke-cli/issues)

### Why No Configuration?

The CLI comes pre-configured with our API key, so you can start using it immediately after installation. No setup, no configuration files, no API keys needed!

## 📚 Documentation

For detailed documentation and examples, visit:
- [GitHub Repository](https://github.com/RifatArefinBD/broke-cli)
- [Issue Tracker](https://github.com/RifatArefinBD/broke-cli/issues)
- [Discussions](https://github.com/RifatArefinBD/broke-cli/discussions)

## 🎯 Try It Out

We've included a demo script to showcase the auto-analyze features:

## 📄 License

This project is licensed under the MIT License.
