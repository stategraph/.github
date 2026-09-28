<p align="center">
  <a href="https://stategraph.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/stategraph/brand-artifacts/c6f63a114680a786452b2f28af87637c66c3ec10/logos/wordmark/stategraph_logo_wordmark_white.svg">
      <img alt="Stategraph" src="https://raw.githubusercontent.com/stategraph/brand-artifacts/c6f63a114680a786452b2f28af87637c66c3ec10/logos/wordmark/stategraph_logo_wordmark_black.svg" width="360">
    </picture>
  </a>
</p>

<h3 align="center">Terraform without the state file bottleneck</h3>

Stategraph runs Terraform and OpenTofu from pull requests, and can store your state as a dependency graph in PostgreSQL instead of a state file.

* **Stategraph Orchestration** plans every pull request on GitHub or GitLab and posts the result as a comment. Policy checks, cost estimates, and approvals run in the review. The apply runs on merge or on a comment. Open source and self-hostable.
* **Stategraph Infrastructure as a Database** stores each state as a graph in PostgreSQL. A plan reads only the resources your change reaches, changes that touch different resources apply at the same time, and you can query every state with SQL. Works from the CLI with any CI.

Start with [stategraph/stategraph](https://github.com/stategraph/stategraph) or the [quickstart](https://stategraph.com/docs/get-started/quickstart).

[**Website**](https://stategraph.com) · [**Docs**](https://stategraph.com/docs) · [**Blog**](https://stategraph.com/blog) · [**Slack**](https://stategraph.com/slack)

<sub>hello@stategraph.com</sub>
