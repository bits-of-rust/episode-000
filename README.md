# episode-000
Where we install Rust

## Setup
The following needs to be prepared:

* a browser with the landing page for the [Rust][rust-lang] language.
* Already downloaded [package installer][installer].

## Script

In this screen cast we are going to install [Rust][rust-lang] onto our computer. Rust runs on various platforms, and there are installers for all the popular ones.

The install button does a pretty good job of figuring out your environment, so go ahead and download the installer.

If the download is finished run the installer. This will guide you through the process of setting up your system for [Rust][rust-lang]. You need to agree with the license before you can install, decide who is going to be able to use Rust on your system. For ease of use click through the installer and provide you administrator password.

After the installer has finished, open a terminal and verify that rust is installed correctly by typing the following command in your terminal.

```sh
rustc --version
```

You will be greated by a version number, a commit hash and a commit date

```
rustc 1.2.0 (082e47636 2015-08-03)
```

[rust-lang]: https://www.rust-lang.org/
[installer]: https://static.rust-lang.org/dist/rust-1.2.0-x86_64-apple-darwin.pkg
