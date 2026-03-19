<!-- eva-project-authority -->

# GitHub Copilot Instructions -- 54-ai-engineering-hub

**Project**: AI Engineering Hub learning and curation repo  
**Path**: C:\eva-foundry\54-ai-engineering-hub\

## Start Here

1. Complete workspace bootstrap first.
2. Query the live project record:
	```powershell
	Invoke-RestMethod "$($session.base)/model/projects/54-ai-engineering-hub"
	```
3. Read local docs in this order:
	- README.md
	- PLAN.md
	- STATUS.md
	- ACCEPTANCE.md

## Project Role

This repo is a broad AI engineering learning hub and sample catalog. Much of its value is in curated reference content and upstream example material. EVA-specific work here should focus on curation, indexing, governance overlays, learning paths, and integration guidance rather than mass rewriting the imported sample corpus.

## Working Rules

- Preserve upstream project examples unless the task explicitly targets one.
- Make EVA-specific additions clearly separable from imported or third-party content.
- Prefer repo-level navigation, metadata, evaluation guidance, and learning structure over sweeping content edits.
- If you update the README or top-level catalog, ensure counts, categories, and links remain internally consistent.

## Validation

- Validate only the examples or documents you change.
- For catalog changes, verify paths and link targets.
- Update STATUS.md when the repository scope or curated structure materially changes.

## Traceability

Use project story tags when traceability is required:

```text
EVA-STORY: F54-01-001
EVA-FEATURE: F54-01
```

Use Project 48 audit tooling before broad governance changes.

## Boundaries

- Do not replace project-specific context with generic primer language.
- Do not mass-normalize imported content without explicit approval.
- Do not assume one stack or one runtime model across the whole repo.
