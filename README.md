# SHA1 cracker

**Description:** SHA1 brute force cracker written in Rust

## Usage

```
# sha1_cracker <dict.txt> <sha1_hash>
# for example
$ sha1_cracker dict.txt 7c6a61c68ef8b9b6a061b28c348bc1ed7921cb53
# or
$ sha1_cracker dict.txt 95401a269a87015f51c501aa2bfff8428713b848
```


## Run

```
$ cargo run -- dict.txt 7c6a61c68ef8b9b6b061b28c348bc1ed7821cb53
```


## Build

```
$ cargo build
```