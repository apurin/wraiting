---
name: wraiting
description: >-
  Use when creating, reviewing, or refining text intended to instruct or supply
  context to an AI, including skills, specifications, plans, prompts, tool
  descriptions, and runtime context templates.
---

# AI-facing authoring

Optimize for **minimal sufficient context**: the smallest set of authoritative
instructions and non-obvious knowledge that reliably produces the intended
behavior.

## Trigger-only descriptions

Treat a skill’s `description` as routing metadata. State only the user intents,
task conditions, or artifact states that warrant loading and using it. Place
objectives, capabilities, and procedures in the body.

## High information density

Preserve hard-earned knowledge, binding decisions, non-obvious constraints, and
operational instructions. Remove narration, generic advice, restatements, and
consequences a competent model can immediately derive without research or tool
calls.

Judge inferability against the intended consumer’s available context and
expected baseline knowledge, not the author’s conversation history. Retain
explicit guidance where a known failure shows that inference alone is
insufficient.

Retain examples, snippets, and explanations only where they resolve ambiguity
or encode information the surrounding instructions do not adequately convey.

Prefer established, semantically precise terminology over explanatory
paraphrases when it preserves the intended meaning. Use consistent terms for
the same concepts and distinct terms for meaningful distinctions. Qualify
overloaded terms and define local meanings where needed.

## Authority and statement status

Distinguish **derivability from authority**. An obvious requirement may still
need explicit expression because inference does not make it binding. Apply the
inferability test to explanatory content, not indiscriminately to requirements,
acceptance criteria, precedence, or stopping conditions.

Preserve each statement’s status, scope, and requirement strength. Distinguish
requirements from proposals, assumptions, and descriptions of current or
planned behavior. Keep conditions and qualifications attached to the statements
they govern.

## Purpose-bound content

Evaluate every passage against the artifact’s intended consumer, task, and
scope. Maintain the current operational contract.

Keep work receipts, progress reports, conversation history, reasoning
transcripts, and incidental discoveries outside the artifact unless they are
necessary for its use.

## Calibrated abstraction

Distill situational feedback into the underlying requirement or failure mode.
Express it at the scope justified by the available context and intent, rather
than the emphatic wording of an isolated correction.

Preserve binding specifics; generalize incidental circumstances. Keep reusable
guidance in skills and task-specific commitments in specifications and plans.

Do not infer requirements from incidental details of examples. Where the
distinction affects execution, distinguish illustrative examples and open-ended
lists from normative examples and exhaustive lists.

## Affirmative, current-state instructions

State the selected behavior directly.

Retain a negative constraint only when the exclusion itself conveys necessary
information about a live ambiguity, meaningful boundary, or credible failure
mode.

Omit rejected approaches and superseded decisions unless knowing the exclusion
is necessary for correct execution.

## Progressive disclosure and single authority

Keep universally needed instructions in the main artifact. Place conditional
depth in explicitly referenced material with clear loading conditions.

Give each rule one maintained authority. Use references when the consumer can
access them efficiently; include synchronized copies where independent
consumption requires self-contained context.

Keep enough context at the point of use for the model to recognize when a
reference is required.

## Deletion and revision checks

For each passage, ask:

> Would removing this materially increase ambiguity, execution risk, or the
> need to rediscover information?

Delete passages that contribute none of these protections.

After any revision, verify the artifact against current authoritative intent
and requirements. Reconcile affected statements and maintained copies; fix
misleading passages at their source. Update related artifacts within the
authorized scope and flag unresolved conflicts outside it. Judge the result by
**behavioral fidelity**, not token count alone.
