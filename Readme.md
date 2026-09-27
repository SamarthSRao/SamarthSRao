# Samarth S Rao

Final-year engineering student in Bengaluru, looking for new-grad backend and infrastructure roles.

I build systems in Go: database internals, Postgres connection pooling, write-ahead logs, a Git-style object store, and TCP servers.

## Featured projects

- **[tcp_next](https://github.com/SamarthSRao/tcp_next)** — Postgres connection pool. A TCP server on `:5433` pre-dials a fixed pool of backend connections, completes the Postgres startup handshake, forwards query messages, and returns a connection when `ReadyForQuery` reports the session is idle.

- **[Wal-Kv](https://github.com/SamarthSRao/Wal-Kv)** — Write-ahead log writer for a key-value workload. Appends set and delete entries (operation, key, value, timestamp, CRC32) under a mutex and syncs each append to disk.

- **[reactorDb](https://github.com/SamarthSRao/reactorDb)** — Git-style object store. The code defines a blob (data, content type, size, last modified) and a unit test. `project_plan.md` describes content-addressed objects, packfiles, and ref updates.

- **[sbloom](https://github.com/SamarthSRao/sbloom)** — Bloom filter. Sizes the bit array and hash count from an expected item count and false-positive rate, hashes with 128-bit MurmurHash3, and includes a CLI to add names and test membership.

- **[url-shortner-go](https://github.com/SamarthSRao/url-shortner-go)** — URL shortener. A Go Fiber API stores codes in Redis, checks that the input is a URL, takes a custom code or a 6-character id, decrements a per-IP quota, and runs with Redis via Docker Compose.

## Writing

[B+ Trees, Buffer Pools and Blocks](https://samarthsrao.blog/blog/databases) on [samarthsrao.blog](https://samarthsrao.blog).

## Contact

[samarthsrao.xyz](https://samarthsrao.xyz) · [X](https://x.com/Samarthssrao) · [LinkedIn](https://in.linkedin.com/in/samarth-s-rao-7868743a9) · [GitHub](https://github.com/SamarthSRao) · [Samarthz0901@gmail.com](mailto:Samarthz0901@gmail.com)
