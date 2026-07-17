# Contributing

Thanks for wanting to add to this collection! Skills here are small, focused, and easy to review.

## Adding a skill

1. Create a folder under `skills/your-skill-name/`.
2. Add a `SKILL.md` with YAML frontmatter:

   ```markdown
   ---
   name: your-skill-name
   description: "One or two sentences on what it does AND when Claude should trigger it. Be specific about trigger phrases — vague descriptions cause the skill to under-trigger."
   ---

   # Your Skill Name

   Imperative instructions for Claude...
   ```

3. Put any supporting docs in `your-skill-name/references/` and any executable helpers in `your-skill-name/scripts/`.
4. Keep `SKILL.md` under ~500 lines. If it's getting long, move detail into `references/` and point to it.

## Checklist before you open a PR

- [ ] `name` in the frontmatter matches the folder name.
- [ ] The `description` clearly states **what it does** and **when to use it**.
- [ ] No secrets, API keys, or personal data committed.
- [ ] If the skill performs actions on live accounts, it states its scope (e.g. read-only) explicitly.
- [ ] If it's not your own work, the original author is credited and its license permits redistribution.
- [ ] Added a row to the catalog table in `README.md`.

## Style

- Write instructions in the imperative ("Pull the data", "Compare against benchmarks").
- Explain *why* a step matters rather than stacking hard rules.
- Prefer clarity over cleverness — someone should be able to skim the skill and know what it does.
