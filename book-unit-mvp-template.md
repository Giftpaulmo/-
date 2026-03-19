# Book Unit MVP Template

## Core Principle

We use high-quality, low-burden reading units to send people back into books.

This is not a bookstore.
This is not a quotes feed.
This is a problem-first reading entry product.

Success has two forms:

- The user continues reading with our product.
- The user continues reading the original book.

Both count as success.

## What To Do Today

Complete these 3 tasks today:

1. Decide the first 3 user problems.
2. Produce the first 5 reading units.
3. Put them into a simple manual prototype and test with 3-5 real users.

Do not build an app today.
Do not design a recommendation algorithm today.
Do not think about scale today.

## Step 1: Pick The First 3 Problems

Use only concrete, common, non-medical problems.

Recommended first 3:

- I cannot start.
- I know what to do, but I do not stick to it.
- I want to read, but I cannot settle down.

Avoid these as first-entry labels:

- I am broken.
- Nothing matters.
- I am anxious all the time.
- I need healing.

The first screen should ask:

"What do you want help with right now?"

## Step 2: Reading Unit Template

Each unit should solve one small problem.
Each unit should be readable in 2-7 minutes.
Each unit should have a clear next step.

Use this template for every unit:

### Unit ID

`U001`

### Problem

`I know what to do, but I do not stick to it.`

### User State

`Wants to improve, but keeps falling back into old patterns.`

### Book

`Atomic Habits`

### Author

`James Clear`

### Source Type

Choose one:

- Public domain original
- Self-translated public domain
- Licensed excerpt
- Original retelling

### Why This Unit

Write one sentence:

`This unit helps the user stop obsessing over goals and focus on systems.`

### Opening Line

Use 1-2 sentences to frame the problem, without overexplaining:

`Maybe the problem is not that you lack goals. Maybe your environment keeps pulling you back into the same routine.`

### Core Reading Unit

Rules:

- 2-7 minutes to read
- One complete idea only
- No fake inspiration
- No extra preaching

### What The User Should Get

Choose only one:

- Relief
- Clarity
- Reframing
- Action cue
- Motivation to continue reading

### End Bridge

After the unit, give only 3 choices:

- Continue this idea
- Continue this book
- Save for later

### Continue This Idea

This should lead to:

- another unit on the same problem, or
- a deeper unit on the same concept

### Continue This Book

This should say exactly what to read next:

`If this idea helped, read the next section on environment design. That is where the book turns the idea into something practical.`

### Save For Later

This should store:

- unit id
- problem
- book
- theme

### Notes After Testing

Capture:

- Did the user finish it?
- Did the user say "this is useful"?
- Did the user want the next unit?
- Did the user want the original book?

## Step 3: Unit Quality Checklist

Before a unit goes live, check all 8:

- It solves one small problem.
- It can stand on its own.
- It does not depend on too much earlier context.
- It is readable in one sitting.
- It sounds calm, not preachy.
- It has a clear bridge after reading.
- It does not make medical promises.
- It is legally safe for the source type.

If 2 or more fail, do not publish it.

## Step 4: First Prototype Template

Build a manual prototype in Feishu, Notion, Figma, or a simple webpage.

Structure:

### Page 1: Entry

Title:

`What do you want help with right now?`

Buttons:

- I cannot start
- I cannot stick to it
- I want to read, but I cannot settle down

### Page 2: Reading Unit

Show:

- problem label
- unit title
- 2-7 minute reading body
- source

Bottom actions:

- Continue this idea
- Continue this book
- Save for later

### Page 3: Continuation

If user clicks `Continue this idea`:

- show next unit on the same problem

If user clicks `Continue this book`:

- show next recommended section
- if possible, show legal full-reading path

## Step 5: Simple Data Table Template

Create a table with these fields:

- unit_id
- problem
- book
- source_type
- read_time_estimate
- completed
- clicked_continue_idea
- clicked_continue_book
- saved
- shared
- notes

For each tester, log one row per unit.

## Step 6: The First 5 Units

Use this exact starter mix:

1. Habit change: goals vs systems
2. Reading attention: how to reduce friction
3. Starting before motivation appears
4. Environment beats willpower
5. Small repetition beats intensity

Do not diversify too early.
Stay tightly around one theme cluster first.

## Step 7: Manual Recommendation Logic

Do not use algorithmic ranking yet.
Use this manual rule:

- If user clicks `Continue this book`, keep them on that book path.
- If user clicks `Continue this idea`, keep them on that problem path.
- If user saves but does not continue, next time show a shorter, easier unit.
- If user drops twice, switch source or framing, not just another excerpt.

## Step 8: What Counts As A Good Signal

In the first week, good signals are:

- Users finish units without being pushed.
- Users ask for the next part.
- Users ask where to read the full book.
- Users return for another problem or another unit.

Bad signals are:

- They only screenshot quotes.
- They say "nice" but do not continue.
- They finish units but never open the next step.
- They ask for summaries instead of reading.

## Step 9: Decision Rules After 2 Weeks

Continue if most testers do at least one:

- continue the same idea
- continue the same book
- return for a second session

Rework if most testers say:

- useful, but too long
- interesting, but I would not come back
- I prefer a summary

Stop the current direction if:

- users treat it like a quote card tool
- there is no meaningful continuation behavior
- sourcing safe content becomes too slow or too weak

## Example Unit

### Unit ID

`U001`

### Problem

`I know what to do, but I do not stick to it.`

### Book

`Atomic Habits`

### Why This Unit

`It replaces self-blame with a systems lens.`

### Opening Line

`If you keep missing the version of yourself you planned for, the problem may not be your ambition. It may be your system.`

### What The User Should Get

`Reframing`

### End Bridge

- Continue this idea: `Read the unit on environment design.`
- Continue this book: `Read the next section where the book explains how cues shape behavior.`
- Save for later

## Final Rule

Do not ask:

"How do we make people stay longer?"

Ask:

"Did this unit help the user move one step deeper into reading?"
