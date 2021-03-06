## Cargo 自定义扩展命令

> [ch14-05-extending-cargo.md](https://github.com/rust-lang/book/blob/master/second-edition/src/ch14-05-extending-cargo.md)
> <br>
> commit 6e53771a409794d9933c2a31310d78149b7e0534

Cargo 被设计为可扩展的，通过新的子命令而无须修改 Cargo 自身。如果 `$PATH` 中有类似 `cargo-something` 的二进制文件，就可以通过 `cargo something` 来像 Cargo 子命令一样运行它。像这样的自定义命令也可以运行 `cargo --list` 来展示出来。能够通过 `cargo install` 向 Cargo 安装扩展并可以如内建 Cargo 工具那样运行他们是 Cargo 设计上的一个非常方便的优点！

## 总结

通过 Cargo 和 crates.io 来分享代码是使得 Rust 生态环境可以用于许多不同的任务的重要组成部分。Rust 的标准库是小而稳定的，不过 crate 易于分享和使用，并采用一个不同语言自身的时间线来提供改进。不要羞于在 crates.io 上共享对你有用的代码；因为它很有可能对别人也很有用！