# Hash Tables Cheat Sheet

- A hash table (or hash map) is an array-based data structure.
- It uses a hash function to convert keys into indices where values are stored.
- Keys are unique, and each key maps to a specific value.
- Hashing is the process of converting a key into a hash code (usually an integer).
- A good hash function minimizes collisions (different keys mapping to the same index).
- Common hash functions include modulo and various cryptographic algorithms.
- put(key, value): Insert a key-value pair into the hash table.
- get(key): Retrieve the value associated with a given key.
- remove(key): Delete a key-value pair from the hash table.
- containsKey(key): Check if a key exists in the hash table.
- Fast retrieval and storage of key-value pairs (average time complexity is O(1)).
- Ideal for situations where data access patterns are known.
- Hash tables are widely used in databases, caches, dictionaries, and symbol tables.