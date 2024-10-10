# Rust Billing Application

A simple command-line billing application written in Rust. This application allows users to manage bills by adding, viewing, updating, and removing them.

## Features

- Add new bills with a name and amount
- View all existing bills
- Remove bills by name
- Update bill amounts
- Simple and intuitive command-line interface

## Getting Started

### Prerequisites

- Rust programming language (https://www.rust-lang.org/tools/install)
- Cargo (Rust's package manager, included with Rust installation)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/rust-billing-application.git
   ```
2. Navigate to the project directory:
   ```
   cd rust-billing-application
   ```
3. Build the project:
   ```
   cargo build
   ```

### Usage

Run the application using:

```
cargo run
```

Follow the on-screen prompts to manage your bills:

1. Add Bill
2. View Bills
3. Remove Bill
4. Update Bill

Enter the corresponding number to select an option.

## Project Structure

- `main.rs`: Contains the main application logic, including the `Bills` struct and its implementation.
- `menu.rs`: (If applicable) Contains the menu-related functions for user interaction.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Rust community for providing excellent documentation and resources.
- All contributors who participate in this project.
