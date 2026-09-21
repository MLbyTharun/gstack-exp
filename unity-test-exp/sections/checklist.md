<!-- AUTO-GENERATED from checklist.md.tmpl — do not edit directly -->
<!-- Regenerate: bun run gen:skill-docs -->
# Unity Plan Refinement Checklist

Use this checklist to rewrite the plan into a practical Unity execution path.

## Scope and outcomes
- State the narrow user outcome in one sentence.
- Keep MVP scope explicit. Mark non-MVP work as deferred.
- Call out hard constraints (platform, timeline, team size).

## Technical architecture
- Define scene boundaries and ownership.
- Define prefab ownership and variant strategy.
- Define data boundaries: ScriptableObjects, serialized state, runtime state.
- Decide asset loading approach (Addressables or Resources) and why.
- Identify system boundaries between MonoBehaviours and pure C# logic.

## Delivery phases
- Break delivery into 3-4 phases with clear deliverables.
- For each phase, list risks and mitigation.
- For each phase, provide concrete definition of done.

## Testing and quality
- List EditMode coverage targets.
- List PlayMode coverage targets.
- List manual QA scenarios.
- Include at least one performance checkpoint (frame time, memory, load time).

## Release readiness
- Name top 3 failure risks likely to appear late.
- Add rollback/fallback strategy for risky components.
- End with clear decision gate: approve or request focused revisions.
