# Go meetup at Zalando

## When

Tuesday, March 18th 2025

## Location

[Zalando Helsinki](https://www.zalando.fi/)

Runeberginkatu 5D

## Talks

### Introduction to ClickHouse for Gophers

Speaker: **Nikolai Lebedev** ([LinkedIn](https://www.linkedin.com/in/nikolai-lebedev/))

Nikolai introduced the ClickHouse architecture and how a team might use a
column database for fast aggregate data reporting. He showed queries that use
various features of the MergeTree ClickHouse engine and examples of using the
`clickhouse-go` package to work with their API.

- [Slides](./Introduction-to-ClickHouse-for-Gophers.pdf)
- [clickhouse-go](https://pkg.go.dev/github.com/ClickHouse/clickhouse-go/v2)

### Postgres logical replication in Go and PeerDB

Speaker: **Nikolay Kuznetsov** ([LinkedIn](https://www.linkedin.com/in/nkuznetsov/), [GitHub](https://github.com/nikolayk812))

Nikolay presented how one can implement logical replication for PostgreSQL in
Go, the fundamentals of WAL transactions, and had a demo for a minimal
implementation tracking insert operations to integrate with the transactional
outbox pattern.

- [Slides](./postgres-logical-replication.pdf)
- [wal implementation in pgx-outbox on GitHub](https://github.com/nikolayk812/pgx-outbox/tree/main/wal)

### GenAI with langchaingo and Ollama

Speaker: **Maryum Hamid** ([LinkedIn](https://www.linkedin.com/in/maryum-hamid-6657231aa/))

In her lightning talk, Maryum gave a demo on using `langchaingo` and Ollama
to run a conversational model with message history and LLaVa for image
recognition.

- [Slides](./GenAI-with-LangchainGo-&-Ollama.pdf)
- [langchaingo](https://github.com/tmc/langchaingo)
- [Ollama](https://www.ollama.com/)

