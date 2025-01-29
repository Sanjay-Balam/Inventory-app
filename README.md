# Tauri + Nextjs (TS)

This template helps you get started with Tauri using vanilla HTML, CSS, and TypeScript.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/)
- [Tauri VSCode Extension](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode)
- [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

## Steps to Set Up the Tauri App After Cloning

Follow these steps to set up and run the Tauri app after cloning this repository:

### 1. Clone the Repository

First, clone the repository to your local machine using the following command:

```bash
git clone https://github.com/Sanjay-Balam/Inventory-app.git
cd Inventory-app
```

2. Install all the Dependencies 
```js
bun i 
```
3. Install Rust Dependencies
```js
cargo install tauri-cli
```

4. Install Rust
```js
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

After installing, verify the installation ```rustc --version```

5. Run this command in the root directory of the project 
```cargo tauri dev```