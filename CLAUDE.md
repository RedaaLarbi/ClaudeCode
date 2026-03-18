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

After completing any meaningful unit of work — a new feature, a bug fix, a refactor — stage the relevant files, commit with a clean descriptive message, and push to `origin/main`. Do not batch up many unrelated changes into a single commit. The goal is that the GitHub remote always reflects the latest working state so nothing is ever lost.
