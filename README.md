# VulkanMemoryAllocator-Hpp
These bindings use all the handy stuff from `Vulkan-Hpp`: wrapper classes, type safe enums, `std::vector`s, `Optional` etc. They are generated by the generator used by `Vulkan-Hpp`, that's why they look so similar.

Current VMA version: 2.2.0

Usage
--
```c++
// In *one* source file:
#define VMA_IMPLEMENTATION

// If you don't like the `vma::` prefix:
#define VMA_HPP_NAMESPACE <prefix>

#include "vk_mem_alloc.hpp"
```
