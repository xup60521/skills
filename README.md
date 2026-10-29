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

`html-summary` was imported from the local global skill.

AgentFlow is my fork of [agfnow/agentflow](https://github.com/agfnow/agentflow). I needed Windows support, so I decided to maintain my own version. It was imported into this collection from [xup60521/agentflow](https://github.com/xup60521/agentflow). It now uses upstream v9.1.0 with the personal Windows, OpenCode, T3 and environment-link ports described in [the fork notes](skills/agentflow/FORK.md). The self-contained skill includes its [Apache-2.0 license](skills/agentflow/LICENSE) and [v9 release history](skills/agentflow/CHANGELOG.md). The original v8 history remains in [docs/agentflow-changelog.md](docs/agentflow-changelog.md).
