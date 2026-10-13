Recently finished my MS in Computer Science at UNT. I build AI and backend systems, and care about what happens when they fail.

| Project | What it is | Verified |
|---|---|---|
| [rental-faq-voice-assistant](https://github.com/vamsi513/rental-faq-voice-assistant) | Voice assistant over a policy corpus, with streaming and confirmation gated tickets | 265 Python and 15 TypeScript tests. n8n verified against a local Docker instance. First delta P50 1.08s on loopback, no speech layer |
| [installment-ledger](https://github.com/vamsi513/installment-ledger) | Loan and payments API with a double entry ledger enforced by a database trigger | 256 tests on real Postgres, including 24 concurrent payments sharing one idempotency key |
| [agentiq](https://github.com/vamsi513/agentiq) · [demo](https://agentiq-platform.vercel.app) | Research assistant that routes between retrieval and live web search | 291 tests |
| [device-control-demo](https://github.com/vamsi513/device-control-demo) | MQTT commands to simulated devices, with acks and retries | 75 tests against a real broker. At least once delivery, effectively once application while a device stays up |
| [evalforge](https://github.com/vamsi513/evalforge) · [demo](https://evalforge-platform.vercel.app) | LLM evaluation platform with pluggable judges | 169 tests |
| [kvnet](https://github.com/vamsi513/kvnet) | Key value server over TCP | 29 protocol assertions plus 13 socket tests |
