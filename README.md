# LRU-CACHE
Provides a thread-safe implementation of a Least Recently Used (LRU) Cache for Julia.

An LRU Cache is a useful associative data structure (AbstractDict in Julia) that has a set maximum size (as measured by number of elements or a custom size measure for items). Once that size is reached, the least recently used items are removed first. A lock ensures that data access does not lead to race conditions.

A particular use case of this package is to implement function memoization for functions that can simultaneously be called from different threads.

## CACHE
A cache is a special storage space for temporary files that makes a device, browser, or app run faster and more efficiently.
After opening an app or website for the first time, a cache stashes files, images, and other pertinent data on your device.
Cached data is used to quickly load an app or website for every subsequent visit.



