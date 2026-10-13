# infra

Super Good infrastructure: cloud resources and deploy pipelines.

## Read first
- [agent-workflow.md](https://github.com/super-good-sg/document-specs/blob/main/docs/agent-workflow.md) and the [CLAUDE.md standard](https://github.com/super-good-sg/document-specs/blob/main/docs/claude-md-standard.md).
- The spec, contract or ADR linked from your Linear ticket (project SuperGood). Linear is the source of truth for work.

## Commands
- Build / plan: TODO (set when IaC tooling is chosen)
- Test: TODO
- Lint: TODO

## Folder map
- Empty apart from README and this file. Folders: TODO (added when IaC tooling is chosen).

## Where things live
Specs, ADRs and contracts (OpenAPI, order schema) all live in [document-specs](https://github.com/super-good-sg/document-specs). See the [standard](https://github.com/super-good-sg/document-specs/blob/main/docs/claude-md-standard.md#where-things-live-all-in-document-specs) for paths.

## Conventions
- Branch name is the Linear `gitBranchName`. One ticket, one branch, one PR. Never merge your own PR.
- Reuse approved patterns; stop and ask before adding a new library or convention.
- No secrets in code or commits.
- Anything that changes cloud resources or spends money needs explicit approval. Plan/preview first; never apply on your own.

## Do not touch
- Production resources and state.
- Credentials and Key Vault contents. Never print, copy or commit them.
