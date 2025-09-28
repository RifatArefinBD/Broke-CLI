# 🚀 Broke CLI v2.2.0 - Ultimate AI-Powered Coding Assistant

[![npm version](https://badge.fury.io/js/broke-cli.svg)](https://badge.fury.io/js/broke-cli)
[![Downloads](https://img.shields.io/npm/dt/broke-cli.svg)](https://www.npmjs.com/package/broke-cli)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **✨ NEW in v2.2.0:** Simplified CLI Interface, No Login Required, Enhanced File Management, Conversation History & Undo Functionality!

**Broke CLI** is the ultimate command-line coding assistant powered by Qwen AI. Generate code, analyze projects, fix bugs, and manage your development workflow with natural language commands - now with a clean, simple interface that just works!

## 🌟 Key Features

### 🤖 **AI-Powered Development**
- **Broke AI Integration** (Primary) - Powerful 32B parameter model
- **Natural Language Processing** - Describe what you want in plain English
- **Smart Code Analysis** - Understand your codebase instantly
- **Auto Bug Fixing** - Automatically fix issues and vulnerabilities
- **Intelligent Code Generation** - Create functions, components, and entire files

### 🎯 **Simplified User Experience**
- **No Login Required** - Use immediately without authentication
- **Prompt-Based Interaction** - Just type your request and get results
- **Clean, Minimal Interface** - Focused on what matters - your code
- **Automatic File Creation** - AI generates files with proper names
- **Undo Functionality** - Easily revert file operations

### 💾 **Enhanced File Management**
- **Automatic File Detection** - AI responses parsed for code blocks
- **Smart File Naming** - Files created with AI-suggested names
- **Multi-File Support** - Create multiple files in a single request
- **Conversation History** - Track all your interactions
- **Session-Based Undo** - Rollback entire operation sessions

### 🎨 **Beautiful Terminal UI**
- **Professional ASCII Art** - Clean, modern header design
- **Colorful Output** - Syntax-highlighted code blocks
- **Clear Status Indicators** - Progress and success/failure feedback
- **Interactive Prompts** - Easy-to-use question interface
- **Markdown Formatting** - Rich response formatting

## 🚀 Quick Start

### Installation

```bash
# Install globally via npm
npm install -g broke-cli

# Verify installation
broke --version
```

### Basic Usage

```bash
# Start the interactive mode (no login required)
broke

# Just type your request:
# > Create a React login component with validation
# > Fix the memory leak in my Node.js app
# > Explain how async/await works in JavaScript
```

## 💻 Interactive Commands

Once you start `broke`, you can use these built-in commands:

| Command | Description |
|---------|-------------|
| `help` | Show available commands |
| `login` | Log in to your account (optional) |
| `signup` | Create a new account (optional) |
| `logout` | Log out of your account |
| `undo` | Undo file operations |
| `history` | Show conversation history |
| `clear` | Clear the screen |
| `exit` / `quit` | Exit the application |

## 🛠️ Advanced Features

### File Creation
When the AI provides code, you'll be prompted to save files:
```
Detected 2 file(s) in the response
Save files? (y/n/auto)
```

### Undo Operations
All file operations are grouped into sessions that can be undone:
```
To undo this operation, type "undo" and select session: session_1701234567890
```

### Conversation History
Track all your interactions with the AI:
```
history
```


## 🌟 What's New in v2.2.0

### 🎉 Major Improvements
- **No Login Required** - Use all core features without authentication
- **Simplified Interface** - Clean, minimal UI focused on productivity
- **Enhanced File Management** - Better file detection and naming
- **Conversation History** - Track all your AI interactions
- **Undo Functionality** - Revert file operations with ease

### 🔄 Key Features
- **1024 Daily Requests** - Generous usage limits for free users
- **IP Address Tracking** - Usage monitored by IP for fair use
- **Automatic File Saving** - AI-suggested filenames for generated code
- **Multi-File Support** - Create multiple files in one interaction
- **Session-Based Undo** - Rollback entire operation groups

### 🛠️ Technical Updates
- **Broke AI Model** - Using powerful broke-o2 model
- **Supabase Integration** - Optional login and usage tracking
- **TypeScript** - Full type safety and better development experience
- **Enhanced Error Handling** - Better feedback and recovery
- **Improved Performance** - Faster responses and operations

## 📊 Usage Information

### Free Tier (No Login Required)
- **1024 requests per day**
- **Automatic file creation**
- **Conversation history**
- **Undo functionality**
- **No account needed**

### Premium Features (With Login)
- **Extended usage limits**
- **Cloud sync for history**
- **Advanced admin controls**
- **Priority support**

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Thanks to Supabase for authentication and data storage
- Thanks to all the open-source libraries that make this possible
