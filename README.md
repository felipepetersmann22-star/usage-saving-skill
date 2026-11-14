# Usage Saving

Help an agent reduce unnecessary calls, repeated reading and polling while preserving the requested outcome and required checks.

## Try it

```sh
npx skills add felipepetersmann22-star/usage-saving-skill
```

Or copy this repository into your agent's skills directory, keeping its files together. Restart or refresh skill discovery if needed. Review the instructions before installing any third-party skill.

Ask your agent: “Review this workflow for avoidable work. Keep the urgent alert and required reviews, and explain any trade-offs.”

For example, if a non-urgent source is checked 96 times daily but used twice a day, the agent can investigate whether two checks would satisfy its actual deadline. That is a change in run count, not proof of a particular token or money saving.

## How it works

The skill identifies the required result, selects useful evidence, considers batching and existing work, and reports trade-offs. Its [workflow](WORKFLOW.md) mentions related skills, but each is optional and this skill works independently. Platform usage reports are needed for actual consumption and cost. It does not authorize changes to a setup or stop a running task by itself.

## Source and license

Derived from the [original public skill](https://github.com/felipepetersmann22-star/agent-skills/tree/1b7a3d8867363c0ff0dda0f9a117aacb7a16a347/skills/usage-saving). See [credits](CREDITS.md) and the [MIT license](LICENSE).
