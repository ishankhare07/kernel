# kernel

### Requirements
1. On linux
`sudo apt-get install nasm qemu`
2. On mac
`brew install nasm`

### Compiling
`nasm -f bin boot1.asm -o boot1.bin`

### Running
`qemu-system-x86_64 -fda boot1.bin`
