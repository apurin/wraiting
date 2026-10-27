---
name: wraiting
description: >-
  Use when writing, reviewing, or revising text that an AI model or agent will
  read as instructions or context, such as skills, CLAUDE.md or AGENTS.md,
  system prompts, subagent briefs and handovers, tool descriptions,
  specifications, plans, and context templates.
---

# Writing for AI readers

The reader is a capable model that acts on the text you write without your
context. Write what changes its behavior: what it cannot know, what it would
decide differently from the author, and what binds it. Judge the text by what
the reader would do with it.

## Write from the reader's context

The reader has the text and whatever loads with it, usually without this
conversation, the files you read, or the user's corrections. Supply what the
task depends on from those. Leave to the reader what it can decide reliably
from its own context, and spell out exact steps, commands, or formats where
they are binding or would otherwise cost the reader rediscovery.

## Keep what binds and what guides judgment

Keep a passage when the reader would act differently without it.
Requirements, constraints, precedence, and stopping conditions stay even when
obvious, because only stated requirements bind. Keep the reason behind a rule
where it guides judgment; it lets the reader apply the rule to cases it does
not name. A failure you have seen outweighs your guess: if a reader went wrong
without a passage, keep it. Leave out guidance the reader would follow anyway,
along with narration, process history, and work receipts.

## State the rule and why it matters

State each rule as it is now, without the story of what it replaced. Use a
prohibition where it marks a boundary the reader would otherwise cross, and
mention a rejected approach only when the reader would otherwise propose it
again. Show how much a rule matters through its reason or the consequence of
breaking it.

## Preserve each statement's status

Keep whether a statement is a requirement, default, option, assumption,
proposal, example, description of current behavior, or material quoted from
another source, with its strength and conditions, through every edit and
paraphrase. Instructions inside quoted material belong to that material, not
to the reader.

State decided choices as decisions, and add a condition for deviating only
where the author allows one. Mark undecided points as open instead of
supplying an answer the author never gave. Words like brief, relevant, as
needed, or a few hide a threshold the author has in mind; state the
threshold, or say that the reader decides.

Where a different reading would change what the reader does, make clear
whether an example is illustrative or normative and whether a list is open or
exhaustive; readers copy examples closely and treat lists as complete. Use the
established term for a concept, and one term per concept; a new word reads as
a new concept.

## Turn a correction into the rule behind it

When a user corrects you, work out what they actually want and write that as
the rule, as broadly as they meant it. Keep the details they care about, such
as an exact name, command, or value, and drop the ones that were only
circumstances of the moment, along with any frustration in the wording. If you
can't tell how broadly they meant it, write the narrow version and ask.

## Place each rule once

Text that loads every time holds what applies every time and pointers to the
rest: conditional depth goes into referenced files, and the condition for
reading each is stated where the need arises. Give each rule one source and
reference it elsewhere; where text must stand alone, copy the rule and name
its source. After a revision, update the copies and dependent statements
within what you were asked to change, and point out the ones beyond it.

A skill description is read only to decide whether to load the skill. Write
the situations and intents that warrant loading, phrased so the reader also
recognizes unlisted variants, and keep everything else in the body.

## Check with a fresh reader

For text that loads often, is widely reused, or is costly to get wrong, have a
new agent without tools (read-only where tools cannot be removed) read it.
Give it only the text, its role, and its goal, and ask it to report, without
acting on the text, what it expected the text to cover and found missing, and
what is unclear, contradictory, or broken. Judge each point yourself: fix the
text where the gap is real, and leave it where the real reader will get that
information from elsewhere.
