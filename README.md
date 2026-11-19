<img src="assets/grand-blue-cover.png" width="100%" alt="bigstep832 — Grand Blue fan art with Iori and Kohei by the ocean, featuring water and oolong tea jokes.">

<p align="center"><strong>Building things. Going deep. Questioning the tea.</strong><br><sub>Code above sea level. Grand Blue energy everywhere else.</sub></p>

## Hey, I'm bigstep832 👋

I build web apps with React, Node.js, and Python — from collaborative learning sprints to evidence-based conversation review. On the Java side, I explore algorithms, data structures, and software design.

The interesting part for me is what happens beneath the interface: matching people across time zones, connecting a video call, tracing a score back to its evidence, or checking an algorithm against an independent oracle.

[Explore my projects](#projects-worth-a-deep-dive) · [Toolbox](#toolbox) · [Diving club](#diving-club-config) · [All repositories](https://github.com/bigstep832?tab=repositories)

### Water or oolong tea? 🥃

<p align="center">
  <a href="https://raw.githubusercontent.com/bigstep832/bigstep832/main/assets/oolong-tea.gif"><img src="assets/oolong-tea.gif" width="350" alt="Animated Grand Blue scene: Iori and Kohei discover the diving club's oolong tea."></a>
  <a href="https://raw.githubusercontent.com/bigstep832/bigstep832/main/assets/water-test.gif"><img src="assets/water-test.gif" width="250" alt="Animated Grand Blue water test: a lighter reveals that the supposed water burns."></a>
</p>

<p align="center"><em>Looks like water. Fails the integration test.</em><br><sub>Grand Blue scenes via Tenor · <a href="https://tenor.com/view/oolong-tea-grand-blue-iori-gif-13475090">Oolong tea</a> · <a href="https://media.tenor.com/uM-_uWPq9mAAAAAM/oolong-burn.gif">Water test</a><br>Click either GIF to open the animation directly.</sub></p>

<img src="assets/signal.svg" width="100%" alt="Animated cyan ocean waves and tiny bubbles.">

## Projects worth a deep dive

### 🌊 [Zinlo — learn together, stay in sync](https://github.com/bigstep832/zinlo)

A full-stack MVP for four-week learning sprints: compatible teammates, a shared schedule, structured lessons, private chat, and browser-based video calls.

- **Matchmaking across time zones:** groups of 3–4 learners, eight compatible meetings, and daylight-saving edge cases.
- **WebRTC calls:** peer connections, audio/video, listen-only joining, signaling, and connection cleanup.
- **Learning progression:** server-enforced lesson unlocks based on the schedule and prior completion, with saved work and progress.

`React` `JavaScript` `Node.js` `SQLite` `Vite` `WebRTC` `Luxon`

[Matchmaking logic](https://github.com/bigstep832/zinlo/blob/main/server/matchmaking.js) · [Video peers](https://github.com/bigstep832/zinlo/blob/main/src/video-peer.js) · [Progression rules](https://github.com/bigstep832/zinlo/blob/main/server/progression.js)

### 🔎 [Conversation Quality Analytics — show the evidence](https://github.com/bigstep832/cqa-hackathon)

A team-built hackathon prototype for reviewing support conversations against configurable quality checklists, connecting assessments to transcript evidence and human appeals.

- **Explainable scoring:** weighted criteria, explicit N/A answers, separate violation flags, and deterministic rounding.
- **Evidence-linked review:** transcript highlights, criterion explanations, audio controls, and original versus effective scores.
- **Traceable appeals:** human review stays separate from original evaluations; idempotency keys protect against conflicting duplicate submissions.

`Python` `FastAPI` `Pydantic` `SQLAlchemy` `SQLite` `React` `TypeScript`

[Scoring engine](https://github.com/bigstep832/cqa-hackathon/blob/main/backend/app/domain/scoring.py) · [Review workspace](https://github.com/bigstep832/cqa-hackathon/blob/main/frontend/src/ReviewWorkspace.tsx) · [Appeal handling](https://github.com/bigstep832/cqa-hackathon/blob/main/backend/app/services/appeals.py)

### 🧠 [Dynamic programming & string algorithms](https://github.com/bigstep832/daa-assignment-4-final/tree/main/Java/source)

Eight Java algorithms with solution reconstruction, independent oracle testing, and reproducible search benchmarks.

- **Dynamic programming:** LCS reconstruction, optimal adjacent merging with executable merge plans, and iterative tree maximum-weight independent set.
- **String search:** KMP, collision-checked Rabin–Karp, suffix arrays with Kasai LCP, and Aho–Corasick.
- **Verification:** exhaustive and randomized oracles, witness validation, full-limit stress cases, and benchmarks with warmups and repeated runs.

`Java` `Python test tooling` `JSONL`

[Implemented algorithms](https://github.com/bigstep832/daa-assignment-4-final/blob/main/Java/source/Algorithms.java) · [Independent tests](https://github.com/bigstep832/daa-assignment-4-final/blob/main/tests/student/test_solution.py) · [Search benchmark](https://github.com/bigstep832/daa-assignment-4-final/blob/main/tests/student/SearchBenchmark.java)

### 🕸️ [Graph algorithms toolkit](https://github.com/bigstep832/Assignment_3_DAA/tree/main/Assignment_3_Java17_submission)

Six graph algorithms covering connectivity, spanning forests, strongly connected components, and reconstructable routes in DAGs.

- **Spanning forests:** DSU with path compression and union by size, plus independent Kruskal and heap-based Prim implementations.
- **Graph structure:** iterative Kosaraju, topological sorting, and deduplicated SCC condensation edges.
- **Shortest paths:** negative weights in DAGs, 64-bit totals, original-edge route reconstruction, and independent stress tests.

`Java 17` `Python verification` `JSONL`

[Completed implementation](https://github.com/bigstep832/Assignment_3_DAA/blob/main/Assignment_3_Java17_submission/src/Java/Algorithms.java) · [Oracle tests](https://github.com/bigstep832/Assignment_3_DAA/blob/main/Assignment_3_Java17_submission/tests/run_own.py) · [Benchmark](https://github.com/bigstep832/Assignment_3_DAA/blob/main/Assignment_3_Java17_submission/tests/benchmark/Benchmark.java)

### 🗂️ [Visitor pattern — a file tree with rules](https://github.com/bigstep832/visitor-pattern-assignment)

An extensible in-memory file tree built around Visitor, double dispatch, and a sealed Java class hierarchy.

- **Separate operations:** size, predicate search, and statistics visitors share explicit-stack traversal.
- **Tree integrity:** rejects cycles, duplicate siblings, multiple parents, and invalid names.
- **Defensive design:** immutable child snapshots, checked arithmetic, visitor recovery after errors, and focused JUnit tests.

`Java 17` `Maven` `JUnit 5`

[Traversal](https://github.com/bigstep832/visitor-pattern-assignment/blob/main/src/main/java/edu/aitu/visitor/TreeVisitor.java) · [Tree invariants](https://github.com/bigstep832/visitor-pattern-assignment/blob/main/src/main/java/edu/aitu/visitor/DirectoryNode.java) · [Integrity tests](https://github.com/bigstep832/visitor-pattern-assignment/blob/main/src/test/java/edu/aitu/visitor/TreeIntegrityTest.java)

## Toolbox

| Area | Tools used in these projects |
| --- | --- |
| Interfaces | React, TypeScript, JavaScript, Vite |
| Backend & data | Node.js, Python, FastAPI, Pydantic, SQLAlchemy, SQLite |
| Real-time & scheduling | WebRTC, Luxon |
| Algorithms & design | Java 17, data structures, graph algorithms, design patterns |
| Testing | pytest, Vitest, Playwright, JUnit 5, randomized oracles |

## Diving club config

```typescript
const divingClub = {
  activity: "diving, allegedly",
  fuel: "oolong tea",
  trustIssues: ["anything labeled water"],
  debugging: "check the evidence before blaming the ocean",
  rule: "if the tea catches fire, open an issue",
};
```

<details>
<summary>🧊 Emergency tea cabinet — open after a failed build</summary>
<p align="center"><br><a href="https://tenor.com/view/grand-blue-gif-21543758"><img src="assets/not-water.gif" width="440" alt="Grand Blue reaction still: This isn't water!"></a><br><strong>When the variable is called water, but the type is clearly wrong.</strong><br><em>TypeError: expected H₂O, received plot development.</em><br><sub>Reaction still from Grand Blue · <a href="https://tenor.com/view/grand-blue-gif-21543758">lynxlynx / Tenor</a></sub></p>
</details>

<p align="center"><sub>Yes, Grand Blue is a diving anime. We checked the README.</sub></p>
