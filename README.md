# Password Generator

A privacy-focused browser application for generating strong, customizable passwords locally. Passwords never leave the browser and are created with cryptographically secure random values.

## Live demo

[Open the Password Generator](https://slickiwnl.github.io/Password-Generator/)

The application is hosted with GitHub Pages and runs entirely in the browser.

## Features

- Generates passwords from 8 to 64 characters
- Supports uppercase, lowercase, numbers, symbols, and ambiguous-character exclusion
- Guarantees at least one character from every selected character set
- Uses rejection sampling to avoid modulo bias in random selection
- Calculates estimated entropy, strength, and brute-force time scenarios
- Includes accessible keyboard controls, live status feedback, and responsive layouts
- Provides clipboard copying with a fallback for restricted browser contexts

## Security approach

The generator uses the browser Web Crypto API instead of `Math.random()`. Rejection sampling keeps character selection evenly distributed, and a Fisher-Yates shuffle randomizes the final character order.

## Run locally

Open `index.html` in a modern browser. No dependencies, build tools, accounts, or backend services are required.

## Publish with GitHub Pages

In the repository settings, open **Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then save. GitHub Pages will publish `index.html` at the project URL above.

## Technology

HTML, CSS, JavaScript, Web Crypto API, Clipboard API, and responsive web design.

## AI-assisted development

Built by Ricardo Macias with AI-assisted review and iteration using Claude Code and OpenAI Codex. Ricardo directed the project, evaluated the recommendations, and owns the final implementation.

## Disclaimer

Strength and cracking-time estimates are educational approximations. Actual password security also depends on storage methods, rate limiting, password reuse, phishing resistance, and account protections.

