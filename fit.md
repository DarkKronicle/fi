# Fuzzy Interpretation of Time \(F.I.T.\)

A way to interperate time in a way that is not rigid, unlike set amount of times.

## What is FIT

Fit is a standardized system of relative fuzzy time measurements that is designed to fit into everyday conversation.

Within casual relationships, it's common to ask for availability \("When are you available to do _x_"\), and it's just as common to get a vague answer \(_"In a bit...", "Soon-ish?"_\). FIT aims to clear up this confusion, by allowing for a concrete measurement of these casual measurements

## The Table of FIT

* `x` refers to the current measurement/modifier.
* All of these times are uncertain to a degree of +-5%.
* If refering to longer period of times \(days\), you can explicitly state 'in a \[time\] amount of \[measurement\]', or just get it from context. Example: `I will get to that in a soon amount of days`.

### Measurements

Different measurements of time

| Measurement | Shorthand | Relationship | Operator |
| :--- | :--- | :--- | :--- |
| Long | L | 4 Short | \* |
| Short | S | 0.25 Long | \* |
| Min | m | 0 &lt; x &lt; 3/60 Long | \* |
| Sec | s | 0 &lt; x &lt; 1/60 Long | \* |
| Bit | B | 0.66 Long | \* |
| Late | l | 1.5 Long | \* |
| Eventually | E | 0 &lt; x &lt; ∞ time | ! |
| Right Now | rn | 0 | ! |

### Modifiers

How to modify measurements.

| Modifier | Relationship | Operator |
| :--- | :--- | :--- |
| No\(t\) | none | ! |
| er | 0.5 &lt; x &lt; 1 | \* |
| en | 1 &lt; x &lt; 1.5 | \* |
| Ish | 0.5 &lt; x &lt;= 1.5 | \* |
| Maybe | 1 or ∞ | =/ |
| A while | 2 &gt; x &gt; .9 | \* |
| + | 1 &lt; x &lt; 2 | \* |
| - | 0.1 &lt; x &lt; 1 | \* |

### Operators

How measurements and modifiers manipulate each other.

| Operator | Description |
| :--- | :--- |
| \* | Multiply |
| + | Add |
| - | Subtract |
| =/ | Split. It creates two possible situations, both need to be taken into account. |
| ! | Override. This defines that whatever previously happened is now overriden by this operator. |

### Flow Aliases

Ease of saying and typing. These are made up of measurements and modifiers.

| Alias | Expanded |
| :--- | :--- |
| Soon | A while short |
| Later | Late ish |
| Some | Maybe ish |
| Little `x` | `x`er |
| Few | Sooner |

### Understanding Variables

There are two main forms of relational time, short, and long. Typically we suggest that a 'long' be defined by 60 minutes, and a 'short' be 15 minutes \(as shown in the table.\) Both of these variables can flex and are uncertain. To combine different measurements and modifiers, use previously defined parts and then follow the operator in the third column.

## Examples

Now you know what everything is, here's how you can use this.

1. I'll be free in a bitish.

   `Sometime between 20 minutes and an hour, closest to 40 minutes.`

2. I'll get to it sooner.

   `Within the next 15-20 minutes.`

3. Soon

   `Within the next 10 to 30 minutes.`

## Other

Feel free to share this with whoever, whenever, wherever! F.I.T. is meant to be used in any context. You can create an issue to propose an update, or a pull request to change whatever.

