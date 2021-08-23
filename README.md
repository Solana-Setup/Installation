# Solana installation
![img name](https://nomics-api.s3.us-east-2.amazonaws.com/static/images/currencies/SOL2.jpg)

This is a brief overview of how to get up and running on the Solana blockchain.  This guide is specifically for developing on Solana.  Please check the repo for other related guides.

[Official developer page](https://solana.com/developers)

#
#
# Install Rust

Solana and its smart contracts are written in Rust.

###### For MacOS, Linux, or another Unix-like OS

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Reference - [Installing Rust (Official website)](https://www.rust-lang.org/tools/install)


## Create a Rust project

```
cargo new name_of_project
```

This command will create a new directory in your current working dir, containing:
1. a git repo;
2. `src` directory containing a `main.rs` file;
3. the project config file `cargo.toml`;

[Learn Rust](https://doc.rust-lang.org/book/title-page.html)

---


# Install the Solana Tool Suite

##### For MacOS and Linux

```
sh -c "$(curl -sSfL https://release.solana.com/v1.7.10/install)"
```
You can replace `v1.7.10` with the release tag matching the software version of your desired release.

##### For Windows
Please refer to https://docs.solana.com/cli/install-solana-cli-tools#windows

### Confirm Solana is installed

`solana --version`
