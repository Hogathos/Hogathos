# Hogathos

Network Administration student, GRCC Winter 2027, building Iris, an agent observability proxy.

[![Website](https://img.shields.io/badge/Website-agentia--mechanici.pages.dev-blue?style=for-the-badge)](https://agentia-mechanici.pages.dev)
[![GitHub](https://img.shields.io/badge/GitHub-Hogathos-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hogathos)
[![Substack](https://img.shields.io/badge/Substack-%40thehogsanctuary-orange?style=for-the-badge&logo=substack&logoColor=white)](https://substack.com/@thehogsanctuary)

---

### About Me

- Student, GRCC Network Administration A.A.A.S., Winter 2027, then GVSU B.A.S. in Computing, AI specialization, ~2029-2031
- Path: Python → networking / sysadmin → DevOps → AgentOps
- Building Iris: Watch, Verify, Steer, Meter, local-first, metadata only, human in loop
- Iris checks what an agent said it did, against what actually happened, by independent read-back. Correct / Incorrect / Unverified. No score. No LLM-as-judge.

### Pinned

- [python-builds](https://github.com/Hogathos/python-builds) — Small Python builds, one folder per project. Iris, an agent observability proxy, local-first, metadata only, Watch / Verify / Steer / Meter, plus calculators and HOI4 tools.
- [hoi4.py](https://github.com/Hogathos/hoi4.py) — Python library for parsing HOI4 save files, binary or plain text, plotting useful information from them.
- [Model-Testing](https://github.com/Hogathos/Model-Testing) — A place where I put the models I mess around with.

### Iris

Iris is a local proxy that watches agent traffic. It sits on port 8888, on loopback only.

It lets a human pause one run, redirect one run, or stop all runs. It journals first, then cuts. A run cannot retry until a human checks it again. It stops unless a human verifies everything is fine.

Tests: 84, CI green. License: AGPLv3. Status: Observe built, Control and Confirm partly built, Measure next, app mode next, second user next.

### Learning

Agentic Ops, DevOps, and Network Administration.
