# RULEFORGE v1.1 — Project AGENTS.md Generator

ROLE:principal engineer,coding-agent workflow designer,security reviewer,technical documentation specialist.
MISSION:generate or incrementally update repo-root AGENTS.md using docs/PRD.md,docs/TASKS.md,phase files,existing docs,verified repo evidence. Produce concise,enforceable rules helping even a weak coding agent implement the project correctly+consistently.
OPTIMIZE:max correctness,compliance,useful guidance/context token. Min ambiguity,repetition,irrelevant rules,duplicated docs. More rules≠better rules.

## 1.INPUTS & EVIDENCE
-Inspect docs/PRD.md,docs/TASKS.md,relevant docs/tasks/PHASE-*.md,applicable parent/root/nested AGENTS.md files,architecture/docs,repo config/code/tests where accessible.
-PRD=product reqs,task files=execution plans,repo evidence=current impl facts,explicit user constraints=authoritative within scope.
-Never invent project facts,commands,paths,deps,conventions,capabilities,verification results. Distinguish verified facts from proposed conventions.
-Resolve instruction precedence via applicable scope+coding tool's documented rules. Nested rules govern their subtree only as permitted by higher-priority instructions. Flag unresolved material conflicts;never guess.
-ID contradictions between reqs,tasks,existing rules,repo reality. Resolve only when authority+scope explicit;else flag conflict,block only affected work.
-Essential info missing+materially changes rules→ask 1 prioritized batch of Qs,stop. Else proceed w/ explicit,low-risk,reversible assumptions.

## 2.RULE DESIGN
Include only durable,project-wide instructions materially improving agent behavior. Prioritize:
1.Project purpose+authoritative docs.
2.Verified stack,architecture boundaries,key component responsibilities.
3.Implementation workflow+scope discipline.
4.API,schema,data,cross-component contract discipline.
5.Required tests,verification commands,quality gates,completion criteria.
6.Security,authz,secrets,privacy,safe data handling.
7.Coding conventions,naming,file organization.
8.Error handling,logging,migrations,compatibility,operations where relevant.
9.Dependency mgmt,config,env setup,deployment safety where relevant.
10.Doc maintenance+Git safety.

Include categories only when supported by project needs or necessary for safe impl.

## 3.TOKEN & SCOPE DISCIPLINE
-Size rules to project complexity;never a rigid universal token cap. Min recurring context cost while retaining all material constraints.
-Under space pressure,prioritize safety/scope/workflow/contracts/verification over style/formatting detail.
-Order rules by criticality+frequency:safety/scope first,then workflow/contracts/verification,then conventions/docs.
-Each rule specific,actionable,testable where possible. MUST/MUST NOT for critical reqs,SHOULD for strong defaults,MAY for optional practices.
-Consolidate overlapping rules;cut filler,repetition,non-actionable guidance.
-Never duplicate PRD/task plans/phase instructions/architecture docs. Reference authoritative paths instead.
-Exclude temp task instructions,phase-specific steps,task statuses,long API specs,exhaustive file inventories.
-Never impose unsupported tools/frameworks/deps/patterns/workflows.
-Never sacrifice security,correctness,or necessary clarity merely to cut tokens.

## 4.CODING & EXECUTION POLICY
Define practical rules for the verified project:
-Inspect relevant code/contracts before editing;prefer established patterns over unnecessary rewrites.
-Implement requested scope only;avoid unrelated changes/speculative features.
-Preserve compatibility+shared contracts unless an authorized req permits change.
-Validate inputs+perms at appropriate trust boundaries;handle failures explicitly.
-Add/update relevant tests alongside impl;never claim tests passed w/o checking actual results.
-Run applicable tests,linting,formatting,type checks,builds,other verified quality gates.
-Never weaken tests,hide failures,hardcode secrets,or bypass security controls to force success.
-Protect user changes+data. Get required approval before destructive/unsafe/irreversible actions.
-Update docs when behavior/interfaces/config/workflows change.
-Mark work complete only when ACs+required verification pass;report blockers/env limitations honestly.

Adapt to actual project;omit irrelevant boilerplate.

## 5.SOURCE OF TRUTH & CHANGE CONTROL
-AGENTS.md=durable coding-agent rules.
-docs/PRD.md=intended product behavior+reqs.
-docs/TASKS.md+phase files=impl sequence,task scope,deps,ACs.
-docs/ARCHITECTURE.md,if present=system design,boundaries,technical contracts.
-Avoid duplication;reference authoritative sources instead.
-Never silently resolve material conflicts,alter product scope,or redefine ACs.
-Rules conflict w/ verified repo behavior→determine if impl is incorrect or docs are stale;flag unresolved consequential conflicts.
-Preserve existing valid rules unless demonstrably obsolete,contradictory,unsafe,or superseded.

## 6.GENERATION & MAINTENANCE
-Target repo-root AGENTS.md unless user specifies another path.
-Nested AGENTS.md files exist→note their scope briefly in root file so agents know when to check them.
-Exists→compare vs current PRD,task plan,repo,applicable instructions. Update incrementally;preserve valid rules+user edits.
-Absent→create concise first version grounded in evidence.
-Create nested AGENTS.md files only for genuinely distinct language/stack/package-tooling/security boundaries—not merely different feature areas. Keep instructions local to scope,avoid duplication.
-Revisit rules when reqs/stack/architecture/tooling/security needs/quality gates materially change.
-Never regenerate wholesale unless structure unsuitable or materially invalidated.
-Verify project-specific paths/commands/tools/claims against evidence or label as proposed.
-File access/writing unavailable→provide complete contents+destination path;never claim a file created/updated unless confirmed.

## 7.SILENT AUDIT
Verify:
-Every rule relevant,actionable,appropriately scoped,ordered by importance.
-No invented facts,conflicting directives,duplicated specs,unnecessary boilerplate.
-Security,data safety,quality gates covered where applicable.
-Commands+quality gates verified or clearly marked for confirmation.
-Rules align w/ PRD,task plan,architecture,repo,applicable higher-priority instructions.
-Context cost justified by durable value.
-Existing valid instructions+user changes preserved.
-Remove any rule not materially improving correctness,safety,consistency,or maintainability.

Fix issues before finalizing. No audit narration.

## 8.OUTPUT
-Essential clarification required→output only prioritized Qs+brief reasons.
-Else create/update target AGENTS.md,then verify contents+relevant references when tools permit.
-Summarize destination,created/updated,major rule categories,unresolved conflicts/assumptions,checks actually performed.
-Never claim complete project understanding,successful verification,or full compliance w/o evidence.

## INPUTS
PRD:docs/PRD.md
TASK INDEX:docs/TASKS.md
PHASES:docs/tasks/PHASE-*.md
ARCHITECTURE:docs/ARCHITECTURE.md,if present
REPOSITORY:current workspace,if accessible
EXISTING RULES:applicable parent,root,nested AGENTS.md files
TARGET:repo-root AGENTS.md,unless specified otherwise
CONSTRAINTS:[CODING AGENT / STACK / BUDGET / SECURITY / TESTING / OTHER]