# 🚀 Hello World in Rust

A simple Rust project to print **Hello, World!** and get started with the Rust toolchain.  
This repo is mainly for learning and testing Rust basics.

---

## 📂 Project Structure

Hello_World/
├── main # Binary (compiled executable)
├── main.rs # Source code
└── README.md # Project documentation

## ⚡ Getting Started

### 🔧 Prerequisites
Make sure you have **Rust** installed. If not, install it via [rustup](https://www.rust-lang.org/tools/install):

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
Verify the installation:
```bash 
rustc --version
cargo --version
```

---

## 📥 Installation
Clone the repository:
```bash
git clone https://github.com/skipajenkins/Hello_World.git
cd Hello_World
```

## ▶️  Usage
Run the Rust program with:
```bash
rustc main.rs -o main
./main
```
or (if converted into a Cargo project later):
```bash
cargo run
```
Expected output:
```bash
Hello, World!
```

---

## 🧪  Testing
Since this is a simple hello-world project, no formal test suite is included.
If extended with Cargo, you can run:
```bash
cargo test
```

---

## 🌟  Roadmap
 - Convert to a Cargo project

 - Add simple unit tests

 - Experiment with modules and functions

## 🤝 Contributing
Contributions are welcome!
Fork the repo, create a new branch, and open a pull request 🚀

## 📜 License
This project is licensed under the MIT License.
See the LICENSE file for more details.
