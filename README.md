# Muhammad Waqas

I write the rules, AI agents write the code, and I review the work. Solo developer.

What I take on: business automation, API integrations and MCP servers, in custom code where off-the-shelf tools stop.

## How I build

**Rules first.** A written constitution sits above the work. Implementation decisions are evaluated against it, and it outranks my own instructions in the moment.

**Scoped subagents.** Work is split across agents that each reach only their own part of the project.

**Writer and reviewer are separate.** I approve the plan, one agent writes the code, and a different agent reviews new features against the written rules.

**Context on demand.** In my planning repo, the files every session loads are size-capped by a script, and everything else stays cold until a task needs it, so a session pays only for what it reads. My skills route to the one to three reference files a task needs instead of loading whole.

**Checks that run on their own.** Hooks in the planning repo run a citation gate and flag the docs that depend on a file when that file is edited.

**Decisions on file.** One file per decision: what was decided, why, and what it rules out. Features get their own docs, kept current by their own agent.

The field's name for this layer, the loop an agent works inside rather than the single prompt, is loop engineering.

## Public work

- **[Design Vault](https://github.com/404mw/Design-Vault)**: an open-source web app that keeps UI screens, components, colour palettes and fonts on your own machine. The constitution, the agents and the plan, write, review cycle are in the repo. If you want to see the setup above, read this one.
- **[MARWIX-SKILLS](https://github.com/404mw/MARWIX-SKILLS)**: a Claude Code plugin marketplace, MIT. A Postgres query skill that reads the EXPLAIN plan, won't confirm a diagnosis without it, and re-runs it to verify. Image skills that stop and name what's missing instead of improvising a style.
- **[exile.marwix.dev](https://exile.marwix.dev)**: a full-stack product I built and run alone, live since March 2026. A public website, a dashboard where Discord server owners manage their settings, and a bot backend with game calculators and real-time spam and raid moderation. Built with the constitution and scoped subagents described above. The code is private. The product is live.

## Stack

Python, TypeScript, PostgreSQL, SQLite. Next.js, React, Tailwind. discord.py.

Claude Code: subagents, skills, hooks.

## Connect

- X: [@_marwix](https://x.com/_marwix)
- LinkedIn: [MARWIX](https://www.linkedin.com/in/marwix/)
- Discord: [M.W.](https://discord.com/users/503890038829088788)
