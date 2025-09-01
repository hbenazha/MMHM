# MMHM

MMHM (Memory Mapped Hash Map) is a fast C++ hash map backed by a memory-mapped file.  
It provides **random access** and **persistence** without needing to load everything into RAM.

## Features

- Persistent storage using memory-mapped files.
- Hash map interface with O(1) lookup/insert.
- Suitable for large datasets that do not fit entirely in memory.
