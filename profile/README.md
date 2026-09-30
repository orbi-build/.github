### Orbi turns a GitHub Issue into a reviewed, merged PR and a tagged release.

Label an Issue `ai-ready`. Orbi writes the change in its own worktree and opens a pull request. A second agent reviews that PR against the Issue's acceptance criteria and fixes what fails. Only the reviewed commit is merged, and a tagged GitHub release follows. Your repository and your Issues stay the record of everything that happened.

**Start**

- Self-host (AGPL-3.0): [orbi-build/orbi](https://github.com/orbi-build/orbi) · [docs](https://docs.orbi.build)
- Hosted: [Orbi Cloud](https://orbi.build/cloud/?ref=gh-org). The first 3 merged deliveries are free, no card.

**Check it before you trust it**

- Orbi builds Orbi. Every Issue, review round and release in [orbi-build/orbi](https://github.com/orbi-build/orbi) is public; the [evidence page](https://orbi.build/evidence/?ref=gh-org) walks you through three of them.
- Outside our own repos: Orbi opened [k8e PR #613](https://github.com/xiaods/k8e/pull/613), and the k8e maintainer reviewed and merged it.

**Repositories**

- [orbi](https://github.com/orbi-build/orbi): the engine, with the runner, independent review, merge gate and release
- [orbi-bench](https://github.com/orbi-build/orbi-bench): benchmarks for the delivery harness on real open-source bugs
- [orbi-cloud-docs](https://github.com/orbi-build/orbi-cloud-docs): Orbi Cloud user documentation
- [orbi-website](https://github.com/orbi-build/orbi-website): the site at [orbi.build](https://orbi.build/?ref=gh-org)
- [orbi-design-system](https://github.com/orbi-build/orbi-design-system): design tokens and brand rules

The forks under this organization are where Orbi prepares fixes for upstream open-source projects before they are proposed there.

Questions: [open an Issue](https://github.com/orbi-build/orbi/issues) · support@orbi.build · [@xqliu](https://x.com/xqliu)
