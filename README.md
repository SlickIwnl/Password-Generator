# Password Generator

A simple, privacy-focused tool for creating strong passwords directly in your browser. No download, account, or installation is required.

## Use it online

[Open the Password Generator](https://slickiwnl.github.io/Password-Generator/)

## How to use

1. Choose a password length from 8 to 64 characters.
2. Select the character types you want: uppercase letters, lowercase letters, numbers, and symbols.
3. Turn on **Exclude ambiguous** if you want to remove characters that look alike, such as `0`, `O`, `1`, `l`, and `I`.
4. Select **Generate password**.
5. Select **Copy** to copy the password to your clipboard.

Passwords are generated locally with your browser's Web Crypto API. They are not sent to or stored on a server.

## Features

- Generates passwords from 8 to 64 characters
- Supports uppercase letters, lowercase letters, numbers, and symbols
- Guarantees at least one character from every selected character set
- Uses rejection sampling to avoid modulo bias
- Shows estimated entropy, password strength, and brute-force time scenarios
- Includes accessible keyboard controls and responsive layouts
- Provides clipboard copying with a fallback for restricted browsers

## Run locally

Download or clone the repository, then open `index.html` in a modern browser. No dependencies, build tools, accounts, or backend services are required.

## Technology

HTML, CSS, JavaScript, Web Crypto API, Clipboard API, and responsive web design.

## AI-assisted development

Built by Ricardo Macias with AI-assisted review and iteration using Claude Code and OpenAI Codex. Ricardo directed the project, evaluated the recommendations, and owns the final implementation.

## Disclaimer

Strength and cracking-time estimates are educational approximations. Actual password security also depends on storage methods, rate limiting, password reuse, phishing resistance, and account protections.
