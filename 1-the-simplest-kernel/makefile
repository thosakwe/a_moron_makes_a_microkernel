export ASM=nasm
export ASMFLAGS=-felf32

all: src/boot.bin

run:
	qemu-system-i386 -kernel src/boot.bin

src/boot.bin: src/boot.asm
	$(ASM) $(ASMFLAGS) -o src/boot.bin src/boot.asm
