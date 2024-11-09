# Rust Book Solutions Repository

Welcome to the **Rust Book Solutions** repository! This project contains solutions and implementations of the exercises from the [Rust Programming Language book](https://doc.rust-lang.org/book/). Whether you are a beginner looking to learn Rust or an experienced developer brushing up on your skills, this repository is a comprehensive guide to help you follow along with the exercises and projects in the book.

## Directory Structure

The repository is organized as follows:

```bash
projects/
|-- README.md       # This README file
|-- guessing_game   # Solution to the "Guessing Game" project
|-- hello_cargo     # Basic project showcasing Cargo usage
|-- hello_world     # The "Hello, World!" example
```

## Getting Started

To run any of the solutions in this repository, ensure you have [Rust installed](https://www.rust-lang.org/tools/install). Verify your installation with:

```bash
rustc --version
cargo --version
```

### Basic Commands

Here are some essential `rustc` and `cargo` commands to get you started:

- **Compile a single Rust file using `rustc`**:
  ```bash
  rustc filename.rs
  ./filename   # Run the compiled binary
  ```

- **Create a new Rust project with Cargo**:
  ```bash
  cargo new project_name
  cd project_name
  ```

- **Build and run a project using Cargo**:
  ```bash
  cargo build     # Compiles the project
  cargo run       # Builds and runs the project
  cargo check     # Checks code for errors without producing a binary
  ```

- **Format your code**:
  ```bash
  cargo fmt
  ```

- **Run tests**:
  ```bash
  cargo test
  ```

- **To add new folder without initialising git**:
  ```bash
  cargo new --vcs none {folder_name}
  ```

- **To read dependencies documentations**:
  ```bash
  cargo doc --open
  ```

## How to Use This Repository
1. Clone this repository:
   ```bash
   git clone https://github.com/heymaaz/rust-book-solutions.git
   cd rust-book-solutions
   ```
2. Navigate to the folder containing the project you want to run.
3. Use `cargo run` or `rustc` as shown in the commands above to compile and execute the code.

## Contributing
Contributions are welcome! If you have alternative solutions, optimizations, or additional projects, feel free to submit a pull request.

## License
This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Happy coding and learning Rust!
