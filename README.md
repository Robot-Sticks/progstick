# progstick
Model board progsticks 


# Installation

## Prerequisites

### - Cargo
Install Cargo:
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
#### Installing Cargo

To install the Rust package manager (Cargo), follow the instructions for your operating system:

##### Linux and MacOS
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
Closed and open 
Check if the installation worked:
```
cargo --version
```


## Windows  

1. Download the installer at https://www.rust-lang.org/tools/install and run it.

2. Open the command prompt and check the installation with:
```
cargo --version
```

3. If it does not work, manually configure the environment variables:
```
CARGO_HOME=%USERPROFILE%.cargo
PATH=%CARGO_HOME%\bin
```

4. Try checking the installation again with `cargo --version`.

If you have any issues installing, open a ticket with the error.

### - Hardware
WCHLink-E (Only work with WCHLink-E, no WCHLink).
