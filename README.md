# Что лежит
Полный набор необходимых для запуска ядра линукс на эмулируемом в QEMU versatile-pb инструментов:
- ядро linux
- busybox-1.36.0
- корневая файловая система
- дерево устройств .dtb
- скомпилированный образ ядра 
- скомпилированный busybox
- образ файловой системы 
# Где лежит
`/linux/`					-- гит-репозиторий ядра линукс
`/linux/busybox-1.36.0/`			-- busybox
`/linux/busybox-1.36.0/rootfs/`			-- корень файловой системы эмулируемого устройства
`/linux/arch/arm/boot/zImage`			-- образ ядра, скомпилированный под versatile-pb
`/linux/busybox-1.36.0/initramfs.cpio.gz` 	-- образ корневой файловой системы
`/linux/arch/arm/boot/dts/arm/versatile-pb.dtb` -- дерево устройств 
# testqemuarm
