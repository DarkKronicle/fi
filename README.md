# Fuzzy Interpretation of Time (F.I.T.)

A way to interperate time in a way that is not rigid, unlike set amount of times.

## What is FIT

Fit is a standardized system of relative fuzzy time measurements that is designed to fit into everyday conversation. 

Within casual relationships, it's common to ask for availability ("When are you available to do *x*"), and it's just as common to get a vague answer (*"In a bit...", "Soon-ish?"*). FIT aims to clear up this confusion, by allowing for a concrete measurement of these casual measurements

## The Table of FIT

* `x` refers to the current measurement/modifier.
* All of these times are uncertain to a degree of +-5%.

### Measurements

Different measurements of time

| Measurement | Shorthand | Relationship | Operator |
|-------------|-----------|--------------|----------|
| Long        | L  | 4 Short        | \* |
| Short       | S  | 0.25 Long      | \* |
| Bit         | B  | 0.66 Long      | \* |
| Late       | l  | <= 1.5 Long    | \* |
| Eventually  | E  | 0 < x < ∞ time | !  |
| Right Now   | rn | 0              | !  |

### Modifiers

How to modify measurements.

| Modifier    | Relationship | Operator |
|-------------|--------------|----------|
| No(t)       | none         | !  |
| er          | 0.5 < x < 1  | \* |
| Ish         | 0.5 < x <= 1.5 | \* |
| Maybe       | 1 or ∞       | =/ |
| A while     | 2 > x > .9        | \* |

### Operators

How measurements and modifiers manipulate each other.

| Operator | Description |
|----------|-------------|
| \* | Multiply |
| +  | Add |
| -  | Subtract |
| =/ | Split. It creates two possible situations, both need to be taken into account. |
| !  | Override. This defines that whatever previously happened is now overriden by this operator. |

### Flow Aliases

Ease of saying and typing. These are made up of measurements and modifiers.

| Alias    | Expanded |
|----------|----------|
| Soon     | A while short |
| Later    | Late ish  |

### Understanding Variables

There are two main forms of relational time, short, and long. Typically we suggest that a 'long' be defined by 60 minutes, and a 'short' be 15 minutes (as shown in the table.) Both of these variables can flex and are uncertain. To combine different measurements and modifiers, use previously defined parts and then follow the operator in the third column.

## Examples

Now you know what everything is, here's how you can use this.

1. I'll be free in a bitish.

   `Sometime between 20 minutes and an hour, closest to 40 minutes.`

2. I'll get to it sooner.

    `Within the next 15-20 minutes.`

3. Soon

    `Within the next 10 to 30 minutes.`
