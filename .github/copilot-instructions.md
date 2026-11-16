# Copilot cloud-agent instructions

## Repository status and purpose

This repository is currently a minimal scaffold named `website-discovery-agent`. The only tracked file inspected on the default branch (`main`) is `README.md`, containing only the project title. There is no implementation yet, so the repository does not establish what the agent's intended behavior, users, or architecture should be. Do not infer product requirements from the repository name; use the task/request or ask for clarification when it does not define the desired behavior.

## Stack and layout

- **Project type/runtime/languages:** Not established. GitHub reports no detected language and repository size is 0 KB.
- **Tracked files at onboarding:** `README.md` only. This instruction file is being added under `.github/`.
- **Not present in the inspected tree:** source directories, dependency manifests, build/test/lint configuration, scripts, documentation beyond the README, and GitHub Actions workflows.

There are no architectural modules or entry points to describe yet. When implementation is introduced, first identify the relevant source files and existing conventions; keep changes focused and avoid adding frameworks or dependencies unless the task calls for them.

## Build, test, and validation

No bootstrap, build, run, test, or lint command can currently be documented or validated: the repository has no manifest, scripts, source code, or CI workflow. Do not invent commands such as `npm install` or claim tests pass. Before running a command, check the current repository tree and use instructions in any newly added project documentation or manifests. If a change introduces a stack, document its actual setup and validation commands in the relevant project docs and add or update appropriate tests.

There are no required environment variables, secrets, external services, or optional setup steps evidenced by the current files. No command failures or workarounds have been observed because there are no project commands to run.

## Working guidance

1. Treat the task description and repository documentation as the source of product requirements; the README currently supplies none beyond the title.
2. Inspect the files relevant to the requested change and follow their established conventions. Only search more broadly if this inventory is incomplete or contradicted by the current repository.
3. Add tests and validation appropriate to any implementation you introduce. Report clearly when validation is unavailable, rather than implying it was run.
4. Keep this guide current when adding the project's purpose, architecture, toolchain, scripts, or CI checks so future agents can use verified instructions instead of rediscovering them.
