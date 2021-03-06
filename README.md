# lib-rvqemu

## Introduction

This project is going to show you how can we run bare metal RISC-V codes in a qemu-virt system
emulator without any OS supported. It doesn't aim to be useful since there already exists many
good work(see [reference](#Reference)). However, I think that it is still worth getting our
hands dirty to see what's happened inside the "magic".

You can read my [chinese note](https://hackmd.io/@RinHizakura/BkAZoqyvt) for more
information of this project.
## Run

Compile the library with the "hello" example.
```
make
```

Run the "hello" example in qemu.
```
make qemu
```

## Reference

* [riscv-probe](https://github.com/michaeljclark/riscv-probe)
* [riscv64-in-qemu](https://github.com/rtfb/riscv64-in-qemu)
