# Cernarium: Claim Boundaries for LLM Benchmark Results

## Abstract

A benchmark result is a valid observation within its own frame, never a general truth. Cernarium is a method for keeping the public sentence inside that frame. Its starting rule is plain: a public claim is an authored object. Evidence can support a claim, but it does not write the claim by itself.

Under this method, every public claim names the wider statements it does not license. The boundary is not left to the reader's restraint. A claim that holds inside protocol C must also state that it does not hold across other tasks, other conditions, or other criteria.

A forbidden expansion is not met with silence. Each one carries an allowed replacement, a narrower sentence that stays publishable. The goal is to say only what the frame permits, and to keep saying it usefully.

This note publishes the method rather than a result. It uses a form-only example to show the move from claim to forbidden expansion to replacement, and it discloses no benchmark result. The boundary table is a guardrail for public language, not evidence for any benchmark result.

## Introduction

A benchmark produces more than a score. It produces inputs, outputs, logs, reports, and scoring records. The pile is large. The public sentence drawn from it is small, one line a reader will quote, repeat, and act on.

The danger lives in the gap between the pile and the sentence. The pile is specific to one protocol, one set of items, one scoring rule. The sentence drifts wider on its own. "Higher on this test" becomes "better." "Stable across these rows" becomes "established." A measurement taken inside one frame gets read as a property of the world.

Cernarium refuses the automatic step. A public claim is not computed from the artifacts. It is written. Evidence constrains what may be written, but the sentence is an authored decision, made once and in the open.

The method then makes the boundary explicit instead of implied. A claim does not rely on the reader to stop at the right place. It states its own edge: what it covers, and which wider reading it refuses. That edge travels with the claim in the same sentence, so a quote cannot leave it behind.

## A worked example, form only

The example below uses no real system, no real task, and no real number. It exists to show the shape of the move, nothing more.

Take a benchmark that compares two systems, A and B, under a fixed protocol C: a fixed set of items, a fixed scoring rule, one run each.

The authored claim stays inside the frame:

> Under protocol C, on this item set and this scoring rule, system A scored higher than system B.

The forbidden expansion is the sentence the result invites but does not earn:

> System A is better than system B.

The expansion fails in named ways, not vaguely. The claim says nothing about other tasks, other items, other scoring rules, other runs, or any property of A and B outside C. Each of those is a door the sentence could slip through, and the boundary closes them by name.

The allowed replacement keeps the result useful without letting it grow:

> Under protocol C, system A scored higher than system B. Any wider reading would require other tasks, other conditions, and other criteria, which this result does not cover.

The replacement is shorter than the conclusion a reader wanted, and it still carries something they can use. That is the whole trade. A bounded sentence is not an empty one.

## Conclusion

This note offers a method, not a result. It does not evaluate any benchmark, scoring rule, or model behavior. It does one thing: it keeps a public claim tied to the frame that produced it.

The method has a name, Cernarium, from the Latin *cernere*, to discern, to separate what holds from what does not. The [boundary table](claim_boundary_table.md) accompanying this note is the instrument. A claim, its forbidden expansions, and its allowed replacement sit together, written down, where a reader can check them.

The claim made here is small and bounded, in keeping with the rule it describes. A benchmark result is a valid observation within its own frame. This note gives that observation an edge it cannot quietly cross.
