# 🚀 BobSpark – AI-Powered GitHub PR Assistant

## 📌 Overview

**BobSpark** is an AI-powered GitHub automation assistant built using **IBM Bob, Model Context Protocol (MCP), and Bob Shell** to simplify and automate continuous Software Development Lifecycle (SDLC) operations.

It connects to live GitHub repositories, intelligently analyzes pull requests, assesses code change risks, recommends relevant reviewers, and automates repository maintenance activities.

BobSpark aims to reduce manual effort, improve code review efficiency, and maintain clean and healthy GitHub repositories through AI-driven automation.

## 🎯 Key Features

### 1. Automated Pull Request Discovery
- Connects to live GitHub repositories using GitHub MCP.
- Automatically discovers all open pull requests.
- Retrieves PR details, authors, source branches, and changed files.
- Provides a consolidated overview of repository activity.

### 2. AI-Powered Pull Request Analysis
- Generates structured summaries for every open PR.
- Analyzes modified files and code changes.
- Classifies PRs based on risk: **Low, Medium, and High**.
- Explains the reasoning behind each risk classification.
- Recommends suitable reviewers based on CODEOWNERS, code ownership, and contributor expertise.

### 3. Autonomous Branch Cleanup
- Identifies branches associated with merged pull requests older than 7 days.
- Excludes default, protected, and active PR branches.
- Executes approved branch deletion operations through Bob Shell.
- Verifies cleanup operations using GitHub APIs.
- Generates a cleanup execution report.
