# Stategraph

**Terraform plans in seconds, not minutes.**

```
$ terraform plan                    $ stategraph plan
Refreshing state... [2847]          Computing change cone... [12]
⚠ 3m 47s elapsed                    ✓ Ready in 2.3s
```

Stategraph replaces Terraform/OpenTofu's flat state file with a database-backed dependency graph. With file-based state, any operation locks everything. With graph-based state, teams lock only what they touch.

| Before | After |
|--------|-------|
| Global lock | Resource-level locks |
| Serial execution | Parallel where safe |
| JSON blob | SQL-queryable |
| Parse to audit | Built-in history |

[**Website**](https://stategraph.com) · [**Blog**](https://stategraph.com/blog) · [**Docs**](https://stategraph.com/docs) · [**Discussions**](https://github.com/orgs/stategraph/discussions) · [**Packages**](https://github.com/orgs/stategraph/packages)

---

<sub>hello@stategraph.com</sub>
