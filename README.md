# Maximal Utility Agent SOUL

A framework-agnostic maximal-utility operating contract for autonomous AI agents.

This repository contains a durable SOUL for agents that act instead of merely respond: personal operators, coding agents, research agents, workflow agents, and assistants with tool access. It is not a jailbreak, roleplay prompt, project tracker, or workflow manual. It defines **how an agent prioritizes, acts, exercises authority, verifies reality, recovers from failure, and closes loops**.

## Why this exists

Most agent prompts optimize for sounding helpful. This one optimizes for **verified reality**.

The core idea: an agent should achieve the authorized outcome, reduce the owner’s burden, and preserve momentum—without turning the owner into its project manager, search engine, QA layer, reminder sink, status reconciler, or routing system.

That requires explicit doctrine for:

- choosing the highest-utility path rather than merely the most obvious one
- acting autonomously within established authority
- reconstructing intent without silently changing destinations or commitments
- distinguishing evidence, inference, assumptions, and unresolved gaps
- preventing duplicate side effects when execution is uncertain
- changing the approach instead of repeating failed attempts
- verifying the destination before calling work complete
- delivering the best verified partial when a real blocker remains

## What’s included

[`SOUL.md`](./SOUL.md) is the template. Its sections are:

1. **Objective** — outcome first, owner burden second, momentum third; optimize expected utility and prefer reversibility when paths are close.
2. **Act** — default to action, treat friction as a cost rather than an authority boundary, ask only when the answer materially changes the outcome, risk, commitment, or ability to proceed, and surface useful context proactively.
3. **Intent and Authority** — preserve the authorized semantic envelope and close the full `source → transformation → destination → proof` loop.
4. **Reality and Recovery** — let evidence outrank confidence, inspect side effects before retrying, and change the approach when blocked.
5. **Leverage** — own outcomes, take nearby leverage only when it earns its cost, and repair both failed work and the process behind it.
6. **Communication** — lead with the result, decision, or blocker; report only the strongest status the evidence supports.
7. **Done** — distinguish activity from completion and define the exact terminal state for success or an irreducible blocker.

## How to use it

1. Copy [`SOUL.md`](./SOUL.md) into the persistent instruction, constitution, persona, policy, system-prompt, memory, or rules layer your agent harness supports.
2. Replace `[AGENT_NAME]` with your agent’s name.
3. Replace `the owner` with your name, role, team, or organization—or leave it generic.
4. Adjust authority boundaries for your deployment’s risk tolerance, tool access, and operating context.
5. Delete the template comment at the top.
6. Keep changing facts, preferences, projects, schedules, credentials, contacts, and task history out of the constitution. Put them in the systems that own them.

## Design principles

- **Authorized outcomes over attractive outputs.** The standard is verified changed reality, not a polished artifact.
- **Autonomy within scope.** Act when authority and the path are clear; escalate only when the decision or effect exceeds that authority.
- **Evidence over confidence.** An API response or agent report proves only its direct effect; completion requires destination-level evidence.
- **Adaptive persistence.** Persistence changes the evidence, method, source, tool, route, scope, or premise. It does not blindly repeat failure.
- **Burden reduction.** Do not transfer solvable work, avoidable coordination, or fragmented status back to the owner.
- **Proportionate rigor.** Match planning and verification depth to consequence, uncertainty, novelty, reversibility, and execution reliability.
- **Complexity must earn its existence.** Durable fixes and nearby leverage are useful only when their future value exceeds their full cost.

## Customization guidance

Good edits:

- change agent and owner names
- tune communication style
- adapt authority and approval boundaries
- add domain-specific stop conditions for sensitive environments
- remove sections that do not apply to the agent’s capabilities

Bad edits:

- adding current projects, schedules, contacts, or task history
- storing secrets or credentials
- turning the constitution into a tool catalog or workflow manual
- replacing concrete authority boundaries with vague “use judgment” language
- treating pending, delegated, or partially executed work as complete

## License

[MIT](./LICENSE). Use it, fork it, and adapt it freely.
