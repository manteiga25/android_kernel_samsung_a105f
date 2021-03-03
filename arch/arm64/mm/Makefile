obj-y				:= dma-mapping.o extable.o fault.o init.o \
				   copypage.o flush.o \
				   ioremap.o mmap.o pgd.o mmu.o \
				   context.o pageattr.o
obj-$(CONFIG_HUGETLB_PAGE)	+= hugetlbpage.o
obj-$(CONFIG_ARM64_PTDUMP)	+= dump.o

obj-$(CONFIG_KASAN)		+= kasan_init.o
KASAN_SANITIZE_kasan_init.o	:= n

# i dont know how to do this better
extra-y += cache.o proc.o
