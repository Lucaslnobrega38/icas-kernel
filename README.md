# icas-kernel

Files of the Linux 7.0-rc1 port of Intel's IPC Class-Aware Scheduling (ICAS) patch
series (v4, originally for 6.4-rc1), used in the paper "Challenges of IPC
Class-Aware Scheduling on Raptor Lake Processors in the Linux Kernel".

This repository holds only the kernel files touched by the port, at their
Linux 7.0-rc1 paths. Copy them over a 7.0-rc1 tree and build with
`CONFIG_IPC_CLASSES=y`. Benchmarks: see icas-bench.

Licensed under GPL-2.0, as the Linux kernel.
