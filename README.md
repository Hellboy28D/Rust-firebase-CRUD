# Rust-firebase-CRUD

Rust Firebase CRUD 🚀

A lightweight CRUD application built with Rust and Firebase Realtime Database, demonstrating how Rust can interact with cloud databases using asynchronous programming and clean API handling.

Overview

This project shows how to build a complete Create, Read, Update, and Delete (CRUD) workflow using:

* Rust
* Firebase Realtime Database
* Async programming with Tokio
* Serialization with Serde
* Firebase REST integration

The project is designed as a simple learning and practical implementation for developers exploring backend development with Rust and cloud-based databases.

Features

✅ Create users in Firebase
✅ Fetch a single user
✅ Fetch all users
✅ Update user data
✅ Delete users
✅ Async API requests using Tokio
✅ JSON serialization/deserialization using Serde

Tech Stack

* Rust
* Firebase Realtime Database
* Tokio
* Serde
* firebase-rs

Project Structure

src/
 ├── main.rs
Cargo.toml
README.md

Dependencies

[dependencies]
firebase-rs = "2.0.5"
serde = "1.0.147"
serde_json = "1.0"
tokio = { version = "1.21.2", features = ["full"] }

Setup

Clone the repository:

git clone https://github.com/Hellboy28D/Rust-firebase-CRUD.git

Move into the project directory:

cd Rust-firebase-CRUD

Run the application:

cargo run

Example User Object

User{
    name: "Divakar Daya",
    age: 20,
    email: "example@gmail.com"
}

CRUD Flow

Create User → Read User → Read All Users → Update User → Delete User

Learning Outcomes

This project helped explore:

* Rust async programming
* Working with external APIs
* Firebase integration
* Data serialization and deserialization
* Struct modeling and API response handling

Future Improvements

* Authentication support
* Better error handling
* Environment variable configuration
* Modular project structure
* REST API endpoints with Actix or Axum

Contributing

Contributions and suggestions are welcome.

License

Open-source and available under the MIT License.

⸻

Built with Rust ❤️ and Firebase ☁️
