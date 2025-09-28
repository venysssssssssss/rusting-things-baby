# Copilot Instructions for rusting-things-baby

## Project Overview
This is a Rust learning repository focused on exploring and practicing Rust programming concepts. The project name "rusting-things-baby" suggests this is a beginner-friendly environment for learning Rust development.

## Development Guidelines

### Code Style and Standards
- Follow standard Rust formatting using `rustfmt`
- Use `cargo clippy` for linting and best practices
- Prefer explicit type annotations for learning purposes, even when Rust can infer types
- Write clear, descriptive variable and function names
- Add comprehensive comments explaining Rust concepts for educational value

### Project Structure
- Organize code into logical modules and files
- Use `src/main.rs` for executable projects
- Use `src/lib.rs` for library crates
- Create separate modules for different concepts or exercises
- Include examples in a dedicated `examples/` directory

### Error Handling
- Use `Result<T, E>` for operations that can fail
- Prefer `?` operator for error propagation
- Avoid `unwrap()` and `expect()` in production code, but acceptable for learning examples with clear comments
- Demonstrate different error handling patterns for educational purposes

### Testing
- Write unit tests for all functions using `#[test]`
- Include integration tests in the `tests/` directory
- Use `cargo test` to run all tests
- Add doc tests in comments to demonstrate usage examples
- Aim for comprehensive test coverage to reinforce learning

### Documentation
- Document all public functions and modules with doc comments (`///`)
- Include usage examples in documentation
- Explain Rust-specific concepts like ownership, borrowing, and lifetimes in comments
- Use `cargo doc --open` to generate and view documentation

### Dependencies and External Crates
- Keep dependencies minimal and well-justified
- Prefer standard library solutions when learning fundamental concepts
- Document why external crates are chosen over standard library alternatives
- Update dependencies regularly using `cargo update`

### Learning Focus Areas
- Memory safety and ownership concepts
- Pattern matching and enums
- Traits and generics
- Concurrency and async programming
- Error handling patterns
- Performance considerations

### Build and Development Workflow
- Use `cargo check` for fast compilation checking
- Use `cargo build` for building the project
- Use `cargo run` to execute the main binary
- Use `cargo test` for running tests
- Use `cargo fmt` to format code
- Use `cargo clippy` for additional linting

### Git Practices
- Make small, focused commits with descriptive messages
- Use conventional commit format when possible
- Create branches for different learning topics or exercises
- Include explanatory commit messages that describe what Rust concepts are being explored

### Code Examples and Exercises
- Include inline comments explaining Rust-specific behaviors
- Provide multiple approaches to solving problems when educational
- Demonstrate both functional and imperative programming styles
- Show common pitfalls and how to avoid them
- Include performance considerations and trade-offs

### Safety and Best Practices
- Demonstrate safe Rust patterns
- Show when and how to use `unsafe` blocks (if needed) with thorough explanation
- Prefer compile-time guarantees over runtime checks
- Use appropriate data structures for different use cases
- Consider memory efficiency and performance implications