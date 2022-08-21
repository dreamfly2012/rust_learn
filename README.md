# rust_learn
learn rust by step and examples

## rust 安装

```
RUSTUP_DIST_SERVER=https://mirrors.ustc.edu.cn/rust-static RUSTUP_UPDATE_ROOT=https://mirrors.ustc.edu.cn/rust-static/rustup curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```


## 配置环境变量
将下面的语句添加到配置文件中.bashrc或.zhsrc

```
. "$HOME/.cargo/env"
```

## 配置cargo环境变量

将下面的语句添加到$HOME/.cargo/config 中.

```
[source.crates-io]
replace-with = 'ustc'

[source.ustc]
registry = "git://mirrors.ustc.edu.cn/crates.io-index"
```

## 配置rustup国内源

```
export RUSTUP_DIST_SERVER=https://mirrors.ustc.edu.cn/rust-static

export RUSTUP_UPDATE_ROOT=https://mirrors.ustc.edu.cn/rust-static/rustup
```
