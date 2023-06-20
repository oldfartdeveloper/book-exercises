# README

Reference here when you create a new Rust application.  This is from chapter 1.3.

> You are wasting your time if you try to code Rust without **Cargo**.

In a command line:

```bash
cargo init new-project-name
cd new-project-name
```

It will generate everything you need for:

* Running `cargo`.
* Ignoring the Rust generated output files in `git`.

By doing as much as you can in **Cargo**, you avoid so much IDE instability.  Even **VSCode** defers to **Cargo** for much of what it otherwise would do, but it will be lame if you aren't expressing your intent in **Cargo**.
