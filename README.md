🚀 Prompt-Powered Kickstart: Building a Beginner’s Toolkit for Rust
1. Title & Objective

Title: “Getting Started with Rust – A Beginner’s Guide”

Chosen Tech: Rust 🦀

Why Rust? It’s a safe, fast, and memory-efficient systems programming language that’s becoming popular in web, embedded, and backend development.

End Goal: Install Rust, write a “Hello World” program, and run it successfully.

2. Quick Summary of the Technology

What is it?
Rust is a statically typed, compiled programming language that guarantees memory safety without needing a garbage collector.

Where is it used?

Building web backends (via frameworks like Actix and Rocket)

Game development

Operating system kernels

WebAssembly (wasm) apps

Real-world example:
Dropbox and Cloudflare use Rust to write high-performance, safe backend code.

3. System Requirements

Operating System: Linux / Mac / Windows

Editor/IDE: VS Code (with Rust Analyzer extension
)

Packages:

rustup (Rust toolchain installer)

cargo (Rust package manager & build tool)

4. Installation & Setup Instructions
Step 1: Install Rustup

Run this in your terminal:

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

Step 2: Add Cargo to PATH (if needed)
source $HOME/.cargo/env

Step 3: Verify Installation
rustc --version
cargo --version


Expected output (versions may vary):

rustc 1.80.1 (2025-08-10)
cargo 1.80.1

5. Minimal Working Example
Create a New Project
cargo new hello_world
cd hello_world

Code (src/main.rs)
// Simple Hello World in Rust
fn main() {
    println!("Hello, Moringa AI Capstone!");
}

Run the Program
cargo run


Expected Output:

Hello, Moringa AI Capstone!

6. AI Prompt Journal

Prompt 1:
“Give me a step-by-step guide to set up Rust and run my first program.”

AI Response Summary: Showed how to install rustup, verify with rustc, create a Cargo project, and run Hello World.

Reflection: Saved me from searching through long documentation—clear and concise.

Prompt 2:
“I’m getting a ‘cargo not found’ error after installation. How do I fix it?”

AI Response Summary: Told me to source $HOME/.cargo/env or restart terminal.

Reflection: Direct and effective—fixed my error instantly.

Prompt 3:
“Explain what Cargo does in Rust in simple terms.”

AI Response Summary: Cargo is Rust’s package manager and build system; it helps create, build, and run projects easily.

Reflection: Helped me understand why Cargo is essential, not just a tool I type commands into.

7. Common Issues & Fixes

Problem: cargo not found in PATH.
Fix: Run source $HOME/.cargo/env or restart terminal.

Problem: error: expected ';' during compilation.
Fix: Rust requires semicolons at the end of most statements. Double-check syntax.

Problem: VS Code doesn’t highlight Rust code.
Fix: Install Rust Analyzer extension in VS Code.

8. References

Rust Official Docs

Cargo Book

Rustlings (interactive exercises)

YouTube: Rust Crash Course

🎉 Congrats! You now have a full beginner’s toolkit for Rust. This is structured exactly how Moringa wants: setup guide, runnable project, AI prompt reflections, common errors, and references.

Would you like me to also draft the README.md for your GitHub repo (so your codebase + toolkit stay aligned), or keep this as the final doc for submission?

You said:
yes
ChatGPT said:

Bet 🙌 let’s lock in the README.md so your GitHub repo looks polished and ties neatly to your toolkit doc. Here’s a clean, beginner-friendly version you can drop straight into your Rust project folder:

🦀 Rust Beginner’s Toolkit – Moringa AI Capstone
📌 Project Overview

This project is part of the Moringa AI Capstone. The goal is to learn a new technology (Rust) using AI prompts and create a beginner-friendly toolkit that helps others get started.

This repo contains:

A Hello World Rust project

Documentation on setup & usage

Notes on AI prompts used, reflections, and troubleshooting

🎯 Objectives

Install Rust and Cargo

Run a minimal working “Hello World” program

Document the setup steps and issues encountered

Share AI prompt experiences for learning

⚡ Quick Start
1. Clone the Repository
git clone https://github.com/your-username/rust-capstone.git
cd rust-capstone/hello_world

2. Install Rust
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env

3. Run the Program
cargo run


✅ Expected Output:

Hello, Moringa AI Capstone!

🛠️ Requirements

OS: Linux / Mac / Windows

Editor: VS Code + Rust Analyzer extension

Packages: Rust toolchain (rustc, cargo)

🔍 Common Issues & Fixes

cargo not found: Run source $HOME/.cargo/env or restart terminal.

Missing semicolon error: Rust requires ; at the end of statements.

No syntax highlighting: Install the Rust Analyzer VS Code extension
.

📓 AI Prompt Journal (Highlights)

“Give me a step-by-step guide to set up Rust and run my first program.”
→ Helped scaffold setup & run Hello World.

“I’m getting a ‘cargo not found’ error after installation. How do I fix it?”
→ Solution: source $HOME/.cargo/env.

“Explain what Cargo does in Rust in simple terms.”
→ Cargo = package manager + build system.

📚 References

Rust Official Docs

Cargo Book

Rustlings Exercises

Rust Playground (online editor)

👩‍💻 Author

Capstone by [Your Name]
Moringa School – AI Capstone Project
