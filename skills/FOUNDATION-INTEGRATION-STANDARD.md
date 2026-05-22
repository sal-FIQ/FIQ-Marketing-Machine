# Foundation Integration Standard for All Skills

Use this file as the required pattern for every skill in this repository.

## Required Step 1: Load Foundation Context

Every skill must begin with this exact behavior:

1. Scan `./foundation/` for all `.md` files.
2. For each file, read **only** the header block above the first `---` separator.
3. Compare the current task against:
   - `Load this file when`
   - `Do NOT load this file when`
4. Load the full file only if it is relevant to the task.
5. Skip all unrelated foundation files.
6. Do **not** load all foundation files by default.

## Required Instruction Block

Copy this block into every `SKILL.md` file near the top of the instructions:

```md
## Step 1: Load Foundation Context

Scan `./foundation/` for all `.md` files.

For each file:
1. Read ONLY the header block above the first `---` separator.
2. Check whether the “Load this file when” criteria match this task.
3. Load the full file only if it is relevant.
4. Skip files that do not match.

Do not load every foundation file by default.
Use only the minimum relevant context needed for this task.
```

## Foundation Routing Guidelines

### Usually load `audience-delight.md` when the skill:
- writes audience-facing content
- needs audience vocabulary, pain points, or motivations
- creates social posts, landing pages, emails, blog posts, ad copy, or lead magnets

### Usually load `creator-style.md` when the skill:
- writes or rewrites copy
- needs brand voice, tone, cadence, or formatting style
- creates public-facing messaging

### Usually load `customer-journey.md` when the skill:
- creates nurture flows
- supports stage-specific messaging
- handles onboarding, activation, objection handling, conversion, retention, or expansion

### Usually load `market-positioning.md` when the skill:
- creates launch messaging
- compares against competitors
- defines differentiation, narrative, category framing, or strategic claims

## Optional Review Step

Add a short self-check near the end of the skill:

```md
## Step 3: Self-Review
- Does this reflect the correct audience language?
- Does this match our creator style?
- Does it use the right market position?
- Does it reflect the right customer stage, if relevant?
```

## Important Rule

Skills should not duplicate the full contents of the foundation files. The intelligence should stay centralized in `./foundation/`, and skills should only define:
- task goal
- task workflow
- output format
- quality checks
