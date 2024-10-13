# Rusty Dev Utility

The structure of this repository is based on the [Package Layout](https://doc.rust-lang.org/cargo/guide/project-layout.html) as described in [The Cargo Book](https://doc.rust-lang.org/cargo/index.html).

## Cargo run

The `default-run` manifest key is defined in [Cargo.toml](Cargo.toml).

```
% cargo run
Hi, rusty-dev-utility!
```

Use the `--bin` option to specify a binary.

```
% cargo run --bin good_morning
Good morning!
```

```
% cargo run --bin hello
Hello!
```

```
% cargo run --bin goodbye
Goodbye!
Have a nice day.
```

## LICENSE

This project is licensed under the [MIT license](LICENSE).
