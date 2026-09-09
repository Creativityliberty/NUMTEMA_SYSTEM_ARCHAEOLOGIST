# Nümtema System Archaeologist

Nümtema System Archaeologist (NSA) is an evidence-first reverse-engineering engine. It converts an **authorized local target** into a deterministic, provenance-bearing **System Genome** that can be inspected, validated, and tested for reconstruction sufficiency without silently promoting guesses into facts.

## Releases

### M01 — Genome Core (`v0.1.0-m01`)

M01 establishes the structural pipeline: Target Manifest, minimal classification, Structural Map, Evidence Ledger, source-blind System Genome `0.1.0`, semantic validation, determinism, and structural reconstruction checks.

### M02 — Behavioral & Architectural Recovery (`v0.2.0-m02`)

M02 extends the reference engine with behavioral, architectural, data/state-flow, conformance, and reconstruction gates.

### M03 — Capability Extraction & Artifact Intelligence (`v0.3.0-m03`)

M03 consumes **System Genome `0.2.0` only** and adds source-blind capability mining, autonomy analysis, Tool/Skill/Workflow/Agent/Team artifact intelligence, target-neutral Blueprints, packaging planning, readiness, Goldens, pressure scenarios, and a canonical Transformation Plan.

## M04A — Compiler Kernel & Binding System

M04A consumes the M03 Transformation Plan and target-neutral Blueprints. It validates compilation intake, resolves explicit implementation bindings, preserves the authoritative M03 `compilationOrder`, builds canonical kernel jobs, plans safe deterministic files, and emits an Artifact Bundle skeleton plus Build Receipt.

## M04B — Skillify, Toolify & MCP Compiler

M04B consumes the prepared M04A compilation state and adds specialized **Skill** and **Tool** compilers, deterministic native renderers, Blueprint→Artifact resolution, strict Tool contract normalization, semantic-preservation gates, and a standalone MCP package adapter.

## M04C — Workflowify, Agentify & Teamify Compiler

M04C extends the M04 artifact compiler from Tool/Skill into canonical **Workflow**, **Agent**, and **Team** artifacts while preserving the M03 anti-inflation boundaries. Workflow control flow remains deterministic orchestration; it is never promoted to Agent merely because it contains branches, retries, fallbacks, checkpoints, or state.

Agent compilation preserves decision/planning/operational policies, permissions, constraints, termination, Artifact-ID dependencies, and provider-neutral runtime requirements. An Agent with complete semantics but no execution provider remains `DECLARATIVE_COMPLETE`; an explicitly bound provider can make it structurally `RUNNABLE`, while `runtimeConformance` still remains `unknown` until future runtime evidence exists.

Team compilation requires at least two real Agent artifacts, a shared objective, differentiated responsibilities, and explicit coordination/handoffs where coordination is required. Handoff and responsibility references are lowered from Blueprint IDs to canonical Agent Artifact IDs. M04C remains source-blind and no-execution: it does not start providers, queues, message buses, workflows, agents, teams, or network calls. Agent Plugins packaging remains M04D.

## Verified release

Current verified release: `v0.4.2-m04c`.

Final release SHA-256:

```text
a582d28df1966d43e7871023d68f1ec829fb36e5ae3b3cfaf94b27e866978294
```

Release verification: 440/440 tests, 223 suites, 9 M04C schemas, 9 Golden families, 44 M04C pressure scenarios, plus M04A/M04B regression corpora.
