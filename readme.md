To use this package just paste the following four lines in your console.


```bash
git clone https://github.com/evenpixl/cargo-traffic
cd cargo-traffic
cargo install --force --path .
sh -c 'echo "> cargo $1" && cargo $1' '--' $(cargo --list | grep vr)
```
