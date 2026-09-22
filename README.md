# learn-csc-program

Personal workspace for [CS Primer](https://csprimer.com/). Problem-driven CS foundations — not a dump of course materials.

Keep this repo **private**. Notes are your words; code is your solutions. Link to CS Primer problems instead of copying statements, walkthroughs, or official solutions.

## How to use this

- Suggested path: [CS Primer timeline](/Users/richardemate/.cursor/projects/Users-richardemate-Projects-learn-csc-program/canvases/cs-primer-timeline.canvas.tsx) (open beside chat). First problem: **Computer Systems → Bits and bytes → CSS color convert**.
- Start wherever looks interesting. If unsure, follow that canvas — default is **Bits and bytes**.
- Add a problem folder the day you start it. Do not pre-create empty problem trees.
- Copy `templates/problem/` into the right course/module path.
- One problem, one commit (or a short `wip` then `done` pair).

```
course/                  # one of the folders below
  README.md              # current state of that course
  <module>/
    <problem-slug>/
      notes.md           # goal, approach, what you learned
      src/               # your code
      tests/             # only if the problem needs it
      bench/             # only for perf work
```

## Index

| Course | Status | Current module | Notes |
|---|---|---|---|
| [programming](./programming) | not-started | | [Beyond the Basics](https://csprimer.com/courses/programming/) |
| [systems](./systems) | not-started | | [Computer Systems](https://csprimer.com/courses/systems/) — default start |
| [algorithms](./algorithms) | not-started | | [Algorithms and Data Structures](https://csprimer.com/courses/algorithms/) |
| [networks](./networks) | not-started | | [Computer Networks](https://csprimer.com/courses/networking/) |
| [operating-systems](./operating-systems) | not-started | | [Operating Systems](https://csprimer.com/courses/operating-systems/) — assumes most of Systems |
| [databases](./databases) | not-started | | [Relational Databases](https://csprimer.com/courses/databases/) |
| [distributed-systems](./distributed-systems) | not-started | | [Distributed Systems](https://csprimer.com/courses/distributed-systems/) — leave until later unless motivated |

Status: `not-started` → `active` → `paused` → `done`.

## Language defaults

Override per problem in `notes.md` when needed.

| Course | Default |
|---|---|
| systems, operating-systems | C (assembly where required) |
| networks | C, or whatever you use for sockets |
| algorithms, programming | whatever you already think in |
| databases, distributed-systems | mix is fine; record the choice |

## Related

- Suggested path: [CS Primer timeline](/Users/richardemate/.cursor/projects/Users-richardemate-Projects-learn-csc-program/canvases/cs-primer-timeline.canvas.tsx) — lives in Cursor canvases, not this git tree
- Course how-to: [csprimer.com/how](https://csprimer.com/how/)
- Broader map: [teachyourselfcs.com](https://teachyourselfcs.com/)
- Deep learning (fast.ai → Hugging Face): [learn-deep-learning](../learn-deep-learning)
- Research threads live in [research-lab](../research-lab), not here
