# Public Demo Plan

## Objective

Show that the system can retrieve legal material in a way that is explainable, bounded, and honest about uncertainty.

The demo should prove the method, not oversell the scope.

## Demo story

A user asks a bounded legal question.
The system returns:
- candidate evidence
- exact textual snippets
- relation traceability
- review state where relevant
- an answer or an abstention, depending on evidence quality

## What the demo must show

1. domain-limited query handling
2. exact evidence inspection
3. relation traceability
4. fail-closed abstention when support is weak
5. a visible distinction between reviewed and unreviewed material
6. clear scope disclaimers

## First demo domain

Labor law is the leading candidate because it is:
- practically relevant
- naturally bounded
- easy to explain to a public audience
- compatible with the system's current evidence-first method

Environmental law remains the other core pilot and can be shown as a second example when needed.

## What the demo must not show

- full legal coverage claims
- autonomous legal advice
- unreviewed relations presented as canonical
- private vault contents
- internal lab clutter
- anything that makes the demo look broader than it really is

## Release gate

The demo is ready when:
- the architecture story is clean
- the public docs are coherent
- the evidence narrative is consistent
- the system can visibly abstain when evidence is insufficient

## One-line public description

An evidence-first legal retrieval demo that shows how grounded legal systems should answer only when the record is strong enough.
