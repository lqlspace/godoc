# 问题
- persistentalloc从哪里分配的内存？


# persistentalloc
- 必须在systemstack调用
- persistentalloc-> persistentalloc1 -> sysAlloc  -> mmap
