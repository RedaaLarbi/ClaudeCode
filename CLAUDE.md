# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A collection of browser-based web games and apps — single-file HTML projects with embedded CSS and JavaScript, no build step or dependencies.

## Running / Testing

Open any `.html` file directly in a browser:
```
open tictactoe.html
```

No build, no package manager, no server required.

## Architecture

Each project is a **self-contained `.html` file** with inline `<style>` and `<script>` tags. There are no shared utilities, no frameworks, and no external dependencies.

## Git Workflow

Commit and push to GitHub (`origin/main`) at the end of each completed task. Use clean, descriptive commit messages focused on what changed and why.
