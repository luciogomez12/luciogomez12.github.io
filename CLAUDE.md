# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project overview

`mi-app` is a static, single-file web page: everything lives in `index.html` (markup, an inline `<style>` block and an inline `<script>` block). There are no dependencies, no package manager, no build step, no linter and no tests. It is not a git repository.

## Running

Open `index.html` directly in a browser (double-click, or `start index.html` in PowerShell). Reload the page to see changes.

## Conventions

- Keep the page self-contained in one HTML file: no external scripts, stylesheets or build tooling unless the user asks for them.
- UI text is in Spanish (`<html lang="es">`).
