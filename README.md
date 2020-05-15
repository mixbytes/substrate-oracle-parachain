# Test stand for oracle frame

## Initialize

```console
git submodule update --init --recursive
```

## Run node

```console
cd node
cargo run-test
```
For clean node info you can delete `chain-info` folder in project root.

## Run client
```console
cd client
cargo run
```
