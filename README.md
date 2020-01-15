# WhatSubs

## libraries

### binary heap
* runtime/src/binary_heap.rs
* 实现了最小堆, 参考了Rust标准库中的堆实现.
* 如果有10000只猫, 树高14层.
* 通过测试

### k-ary heap
* runtime/src/kary_heap.rs
* 实现了多叉最小堆, 参考了Rust标准库中的堆实现.
* 如果有10000只猫, k=8时, 树高5层.
* 每个节点的所有子节点, 保存在一起于一个数组中.
* 由于堆保存于磁盘. 减少树高能减少磁盘的IO.
* 通过测试



