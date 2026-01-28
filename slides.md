# Vibe Coding How-To Guide

Operational Instructions for AI-Assisted Development

---

## Command Line Basics

Let's get comfortable with the terminal

---

### What is the Terminal?

A **terminal** (or command line) is a text-based interface for controlling your computer

Instead of clicking buttons and icons, you type commands

Why use it?
- More powerful and precise control
- Essential for development work
- How AI coding agents interact with your system

---

### Opening Your Terminal

**Mac:**

1. Press `Cmd + Space`
2. Type "Terminal"
3. Press Return

**Windows:**

1. Press Windows key
2. Type "PowerShell"
3. Press Enter

---

### Essential Commands

| Command | Description |
|---------|-------------|
| `ls` | List files & folders in current directory |
| `mkdir <name>` | Create a new folder |
| `cd <name>` | Move into a specific folder |
| `pwd` | Show your current location |
| `cd ..` | Move up one level to parent directory |

---

## Installing Gemini CLI

---

### Windows (PowerShell)

1. Install Node.js: [nodejs.org/en/download](https://nodejs.org/en/download)
2. Install Gemini CLI:
   ```bash
   npm install -g @google/gemini-cli
   ```

---

### macOS (Terminal)

1. Install Homebrew: [brew.sh](https://brew.sh/)
2. Install Gemini CLI:
   ```bash
   brew install gemini-cli
   ```

---

### Login Setup

After installation, run `gemini` to authenticate with Google

Choose "Login with Google" and follow the browser prompt

Free tier: 60 requests/min, 1,000 requests/day

---

## Prompt Engineering Basics

How you ask matters as much as what you ask

**Be specific:** "Create a Python function that sorts a list of dictionaries by the 'date' key"

vs. "Help me sort some data"

**Provide context:** Share relevant code, error messages, project structure

**Iterate:** Refine your prompts based on results

---

## Start with a README

Ask the agent to create a README.md file first

This helps you understand and approve the workflow before building

The README should:

Describe your project idea

Outline the project structure

List key features or goals

---

## Resources

**[Claude Code](https://code.anthropic.com/)** - AI assistant for your entire development workflow

**[Google AI for Students](https://gemini.google/students/)** - 1-year free trial (requires SheerID verification)

**[GitHub Copilot](https://github.com/features/copilot)** - AI code suggestions in your editor

**[GitHub Desktop](https://desktop.github.com/)** - Visual Git interface, no command line needed
