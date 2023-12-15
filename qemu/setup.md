
### How to setup a `QEMU` environment

```sh
git clone update --init qemu
cd qemu-build
../qemu/configure --target-list="riscv64-softmmu"
make -j
```