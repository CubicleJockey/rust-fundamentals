# Cargo
> A Package Manager for Rust.

[Rust Crates](https://crates.io/)
[Install](https://crates.io/crates/cargo)
[Documentation](https://doc.rust-lang.org/nightly/nightly-rustc/cargo/)

---

**Check Cargo Version:**
```bash
cargo --version
```

**Initialize a New Project:**
```bash
cargo init .
#This will  create a new project in place and use directory a project name.
#This defaults to `Application` type project
```

```bash
cargo init --lib .
#Same as before but project is created as `Library` not `application`
```

```bash
cargo new foo-bar
#This will  create a new project in place and use foo-bar as project name
#This defaults to `Application` type project
```

```bash
cargo new --lib foo-bar
#This will  create a new project in place and use foo-bar as project name
#Creates as `Library` type project
```