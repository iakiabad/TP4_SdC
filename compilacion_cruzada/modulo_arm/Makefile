obj-m += mimodulo.o

all:
	$(MAKE) -C /home/iakiabad/linux M=$(PWD) ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- modules

clean:
	$(MAKE) -C /home/iakiabad/linux M=$(PWD) clean
