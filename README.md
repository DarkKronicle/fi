# Fuzzy Interpretation of Time (F.I.T.)

A way to interperate time in a way that is not rigid, unlike set amount of times.

## What is FIT

Fit is a standardized system of relative fuzzy time measurements that is designed to fit into everyday conversation. 

Within casual relationships, it's common to ask for availability ("When are you available to do *x*"), and it's just as common to get a vague answer (*"In a bit...", "Soon-ish?"*). FIT aims to clear up this confusion, by allowing for a concrete measurement of these casual measurements

## The Table of FIT

* `x` refers to the current measurement/modifier.

| Measurement | Relationship | Operator |
|-------------|----------|---|
| Long        | 4 Soon | \* |
| Later       | <= 1.5 Long | \* |
| Soon        | 0.25 Long | \* |
| Eventually  | 0 < x < ∞ Long | \* |
| Right Now   | 0 | ! |

| Modifier    | Relationship | Operator |
|-------------|---------|---|
| No(t)       | none | ! |
| en          | Float < 1 | \* |
| Ish         | Float between: 0 < x <= 1.5 | \* |
| Maybe       | 1 or ∞ | =/ |

| Operator | Description |
|---|---|
| \* | Multiply |
| + | Add |
| - | Subtract |
| =/ | Split. It creates two possible situations, both need to be taken into account. |
| ! | Override. This defines that whatever previously happened is now overriden by this operator. |

### Understanding Variables

There are two main forms of relational time, short, and long. Typically we suggest that a 'long' be defined by 60 minutes, and a 'short' be 15 minutes (as shown in the table.) Both of these variables can flex and are uncertain. To combine different measurements and modifiers, use previously defined parts and then follow the operator in the third column.
