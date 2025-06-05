# Locality of Reference

**Locality of Reference** describes how computer programs tend to access the same set of memory locations repetitively over a short time span.

## 🧠 Types of Locality

### Temporal Locality
- **Definition:** If a memory location is accessed, it is likely to be accessed again soon.
- **Example:** Repeated use of a loop counter or variable.

### Spatial Locality
- **Definition:** If a memory location is accessed, nearby memory addresses will likely be accessed soon.
- **Example:** Accessing elements of an array sequentially.

## 📚 Real-world Analogy
- **Temporal:** Reading the same book multiple times.
- **Spatial:** Reading pages in order from front to back.

## 💡 Use in Caching
- Modern CPU caches are designed to exploit both types:
  - **Temporal:** Keep recently accessed data in cache.
  - **Spatial:** Prefetch adjacent memory blocks.

---

**Related Topics:**
- CPU Cache Hierarchy
- Paging and Virtual Memory
