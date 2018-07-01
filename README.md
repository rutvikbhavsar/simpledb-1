• SimpleDB is a multi-user transactional database system written in Java, which interacts with Java client programs via JDBC.

• Implemented the core modules required to access stored data on disk. Modules include Fields & Tuples, Catalog, Buffer pool, HeapPage and HeapFile access methods/Iterators.

• Used HashMap data structure to improve buffer search mechanism.

• Implemented filter and aggregates operators to execute queries over multiple tables.

• Designed an eviction policy to flush stale pages from the buffer pool.