# Micro-Path 03 — EVM Developer Fast-Track (45 mins)

Designed for Solidity/EVM developers who want to quickly understand how to adapt
their existing knowledge to Monad’s architecture and performance model.

---

## Step 1 — EVM Compatibility (5 mins)
Read:
- clarity-cards/05-evm-compatibility.md

Key Understanding:
- Solidity, Hardhat, Foundry all work
- No new VM paradigm
- Tooling remains almost identical

Mental Note:
You already know 70% of what you need.

---

## Step 2 — Key Differences That Matter (5 mins)
Read:
- clarity-cards/02-monad-vs-evm-chains.md

Focus:
- Sequential → optimistic parallel execution
- Performance gains depend on conflict frequency
- Architecture decisions differ for throughput

Ask:
“Where does my app write to shared storage?”

---

## Step 3 — Parallel Execution & Conflict Thinking (10 mins)
Read:
- clarity-cards/03-parallel-execution-simple.md

Apply thinking:
- Break your app into independent flows
- Identify potential shared-write hotspots
- Consider batching, sharding, or user-isolated state

---

## Step 4 — Migration Checklist (10 mins)
Read:
- clarity-cards/09-migration-checklist.md

Tick:
- [ ] Contract Solidity-based  
- [ ] Minimal shared-state dependencies  
- [ ] High read, low shared write patterns  
- [ ] Functions can run independently  

If you fail multiple checks → refactor idea.

---

## Step 5 — Review Idea Patterns (5 mins)
Read:
- clarity-cards/07-idea-patterns.md

Pick:
- 1 idea to port, OR  
- 1 idea to redesign for Monad

---

## Step 6 — Output (10 mins)
Write:

**Original concept:**  
**Monad-optimized version:**  
**Parallel-friendly components:**  
**Expected performance gains:**  

This completes the fast-track.
