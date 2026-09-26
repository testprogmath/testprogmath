# Anna Khvorostianova

Senior Platform Engineer on the Developer Experience team at Flink, based in the Netherlands.

I came to platform work from test automation, and most of what I build removes a wait on another team. At Flink that has meant self-service tooling that takes a test order through its whole lifecycle from a CLI, an API, a developer-portal page or an AI coding assistant; a load-testing platform on Kubernetes, built on the k6 operator and deployed through GitOps; and contract testing with shared Go and Kotlin libraries, rolled out team by team.

The repositories below are personal projects. None of them contain Flink code or data.

## Selected projects

**[apple-podcast-transcriber](https://github.com/testprogmath/apple-podcast-transcriber)**: turning a podcast episode into study material chains several paid calls that can fail halfway, so this Telegram bot checkpoints every stage in SQLite, never automatically retries a call that may already have been billed, checks each model answer against the untouched transcript, and deploys from CI with a readiness check and rollback.
<br><sub>Python · SQLite · ffmpeg · OpenAI API · Telegram Mini App · GitHub Actions</sub>

**[radius-load-poc](https://github.com/testprogmath/radius-load-poc)**: knowing whether a RADIUS server survives a burst of logins needs repeatable traffic, so this harness starts FreeRADIUS in Docker and drives it from a Go client through warmup, steady and spike phases, recording each request as NDJSON for a per-phase latency and error summary.
<br><sub>Go · FreeRADIUS · Docker Compose</sub>

**[cat-care-telegram-bot](https://github.com/testprogmath/cat-care-telegram-bot)**: a family group chat was the only record of a sick cat's feeding and medication, so this bot turns free-text messages into typed events with an LLM and then applies deterministic checks against double counting before anything reaches the daily summary it still posts.
<br><sub>Python · SQLite · OpenAI API · Docker</sub>
