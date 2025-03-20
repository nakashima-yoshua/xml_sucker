# xml_sucker

Extracts data from relational databases and exports it into clean, structured XML files.
Initially supports Oracle, with plans for PostgreSQL, MySQL, and more.

## ✨ Features

- 📦 Export each table as a standalone XML file
- 🔍 Introspect schema metadata automatically
- 🛠 CLI-based configuration (coming soon!)
- 🚀 Lightweight and fast thanks to Rust

## 📚 Planned Support

| Database     | Status     |
|--------------|------------|
| Oracle       | ✅ Supported (v0.1) |
| PostgreSQL   | 🔜 Planned  |
| MySQL        | 🔜 Planned  |
| SQLite       | 🔜 Planned  |

## 🔧 Requirements

- Oracle Instant Client (for Oracle support)
- Rust (1.65+ recommended)

## 🚀 Getting Started

```bash
git clone https://github.com/yourname/xml_sucker.git
cd xml_sucker
cargo run
