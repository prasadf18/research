# research

Notes from things I dig into to understand how systems work one level down. Each topic has its own folder with a write-up.

| Topic | What it covers |
|---|---|
| [postgres-listen-notify](postgres-listen-notify/) | Why Postgres takes one global lock when a transaction that sent a NOTIFY commits, what batching does about it, and what is still unclear |

These are reading and analysis notes. Any numbers in them come from the sources linked at the end of each write-up, not from benchmarks I ran myself.
