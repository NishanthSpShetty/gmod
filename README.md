## gmod

A simple command line tool to generate the go binary module.


### Requirement
1. Rust and cargo must be installed.

### Install

1. clone the repo and run
```
cargo install --path .
```

this will generate the binary and install in cargo bin path or you can manually copy the binary by building
```
cargo build
```

### Run

```
gmod my_first_project
```

this will setup

1. create a directory called `my_first_project`.
2. create basic main function in `main.go`.
3. initialise the module with the name `github.com/NishanthSpShetty/my_first_project`


