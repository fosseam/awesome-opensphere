Contributing

Thanks for helping improve Awesome OpenSphere. This guide keeps contributions fast, friendly, and consistent.

Scope

Focus on open 3D spaces: OpenUSD, glTF, formats, tooling, engines, samples, interop.

Prefer open standards and reference implementations. Closed or purely commercial items are out of scope.

Learning resources are welcome if they are stable, freely reachable, and high quality.

Quality bar

Activity: projects should show signs of life in the last 12 months. Stable specs and archived but authoritative references are fine.

Openness: OSI-approved license for code, or a clear open license for docs and assets.

Clarity: a readable README, docs, or usage examples.

What to add

Tools, libraries, viewers, converters, validators.

Specs, official docs, and high quality primers.

Sample assets, scenes, HDRIs that aid testing and demos.

Integrations in DCCs and engines that improve real workflows.

What not to add

Pure marketing pages or shallow link farms.

Duplicates of items already listed.

Paywalled or login-gated content without a public overview.

Formatting rules

One entry per pull request.

Alphabetical order inside each section. Use ASCII sort, ignore leading A, An, The.

Use this single line format:

- [Name](URL) - short, neutral, one sentence description.

Keep descriptions concise. Avoid hype words and emojis.

Link to the canonical source: main repo or official docs. Prefer https.

If you propose a new section, open an issue first and explain the rationale.

Examples

Good

- [usdview](https://openusd.org/release/toolset.html) - Interactive viewer and inspector for USD scenes.

Not good

- [usdview](https://openusd.org/release/toolset.html) - The ultimate and revolutionary USD tool!!!
- [Some Fork](https://example.com) - Another link to the same tool.

Local checks before you open a PR

Install Node.js 18 or newer.

Run awesome-lint:

npx awesome-lint

Optional link check with lychee:

lychee README.md --accept 200,206,302,429 --exclude-mail --max-redirects 5

If you do not have lychee locally, the CI will run it for you.

Pull request checklist



Review process

Maintainers triage for scope, quality, and format.

Small edits may be applied during review for consistency.

If an item is borderline, we will ask for a short justification or more context.

Maintenance policy

Broken links: we will fix or replace them when possible. If not, the entry may be removed.

Inactive projects: if a project is clearly unmaintained and alternatives exist, we may prune it after discussion.

Section size: when a section grows too large, we may split it or move niche items to a dedicated subsection.

Security and conduct

Be kind and constructive in issues and PRs.

Report security issues responsibly to project owners upstream, not in this repository.

This project follows a standard Code of Conduct. Until a separate file exists, assume the GitHub Community Guidelines apply.

License

By contributing, you agree that your submissions are released under the repository license (CC0 unless noted otherwise).

