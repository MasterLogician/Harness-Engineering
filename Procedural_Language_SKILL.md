---
name: controlled-procedural-language
description: Write or revise operational prompts, procedures, Skills, and agent handoffs as compact controlled language with explicit state, conditions, actions, transitions, and terminal behavior. Do not use for ordinary explanation or creative prose.
version: 0.1.0
---

# Controlled Procedural Language

Preserve source intent, authority, and scope.

Do not add unstated authority, requirements, or control flow.

Do not claim strict ASD-STE100 compliance.

## Vocabulary

`TERMS | VALUES` → `/home/evan/Continuum/_System/Agent Instructions/ALIASES/procedural-language.md`

IF a shared term is unclear
THEN `RESOLVE_ALIAS(term)`.

IF unresolved meaning changes control flow
THEN REPORT the exact ambiguity
AND STOP.

## Principles

- Put each condition before its action.
- Use active imperative verbs.
- Put one instruction in each clause.
- Use short, complete clauses.
- Use one term for one meaning.
- Repeat a noun when a pronoun is ambiguous.
- Separate instructions from explanations.
- Preserve necessary meaning.

## Logic

- Define state before use.
- Use observable predicates.
- Use `WHEN` for events.
- Use `IF` for current state.
- Repeat the predicate subject across `OR`.
- Parenthesize conditions that mix `AND` and `OR`.
- Keep Boolean, enum, reference, and collection values distinct.
- State each mutation and transition explicitly.
- End each procedure with `RETURN` or `STOP`.
- Report unresolved control flow. Do not infer it.

## Procedure

1. Read the source intent, authority, and scope.
2. Resolve shared terms through `RESOLVE_ALIAS`.
3. Classify definitions, state, events, predicates, actions, transitions, and terminal behavior.
4. Compose or normalize the procedure.
5. Remove explanations that do not change execution.
6. Check logical scope and value types.
7. Preserve the source meaning.

## Completion

- Every shared term resolves.
- Every state value is defined before use.
- Every condition is observable.
- Every mixed Boolean expression is parenthesized.
- Every transition names its destination.
- Every procedure ends with `RETURN` or `STOP`.
- No new authority, requirement, or control flow exists.

IF analysis is not requested
THEN RETURN only the procedural text.
