# Reusable Instructions for Foundation Loading

These instructions define a common pattern for any skill that uses the foundation files in this repository. They can be included or referenced from within each skill’s instruction block to ensure consistent and efficient use of the shared context.

## Step&nbsp;1: Load Foundation Context

1. **Scan the `./foundation/` folder** for all `.md` files.
2. For each file you find:
   - Read only the **header block** — the lines above the first `---` separator.
   - Compare your current task against the “Load this file when” and “Do NOT load this file when” criteria in the header.
   - If the criteria match, load the entire file; otherwise, skip it.
3. Do **not** load every foundation file by default. Only load what is relevant to the current task.

This step ensures that each skill pulls in exactly the context it needs without diluting the output with unrelated information.

## Step&nbsp;2: Execute Task-Specific Instructions

After loading the appropriate foundation files, proceed with the specific instructions for the skill you are executing. These instructions will differ by skill (e.g., writing a blog post vs. drafting a launch message) but should always build upon the context you loaded in Step&nbsp;1.

## Step&nbsp;3: Review and Refine

Before finalizing the output, perform a quick self‑review:

* Does the output align with our **creator style**?
* Does it reflect the **audience’s language and motivations**?
* Is it properly positioned against **market narratives and competitors** where relevant?
* Does it address the appropriate **stage of the customer journey** if applicable?

Adjust as necessary to ensure the final work product feels authentic, relevant, and differentiated.