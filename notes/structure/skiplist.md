# structure/skiplist

### 什么是skiplist
![alt text](image.png)
- 在数组中，一组有序序列我们可以通过二分查找时间复杂度做到O(n)
- 但是数组显著的缺点是：
  - 数组一旦分配完毕，继续拓展的开销很大
  - 数组中每个元素所占空间必须相同
- 