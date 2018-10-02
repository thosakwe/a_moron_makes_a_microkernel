export ASM=nasm
export ASMFLAGS=-felf32

all: src/boot.bin

src/boot.bin: src/boot.asm
	$(ASM) $(ASMFLAGS) -o src/boot.bin src/boot.asm

#verify: src/boot.bin
