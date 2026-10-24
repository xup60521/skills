# Skills

Personal agent skills, organized under `skills/` following [Matt Pocock's skills repository](https://github.com/mattpocock/skills).

## Install

Choose skills and agents interactively:

```sh
bunx skills add xup60521/skills
```

Install a specific skill globally:

```sh
bunx skills add xup60521/skills --skill html-summary --global
```

Install AgentFlow in a project, from that project directory:

```sh
bunx skills add xup60521/skills --skill agentflow
```

## Available skills

- [html-summary](skills/html-summary/SKILL.md) creates standalone HTML summaries when requested.
- [agentflow](skills/agentflow/SKILL.md) manages a project notebook with resumable work, planning, and review. Its scripts, references, and guides are included.

## Sources

`html-summary` was imported from the local global skill. `agentflow` was imported from `xup60521/agentflow`, based on [agfnow/agentflow](https://github.com/agfnow/agentflow), with its Apache-2.0 license retained in [LICENSE](LICENSE). The imported AgentFlow release history is in [docs/agentflow-changelog.md](docs/agentflow-changelog.md).
