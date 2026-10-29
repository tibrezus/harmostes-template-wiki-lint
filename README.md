# harmostes-template-wiki-lint

The wiki-lint **template repo** (three-tier phase 3c, ADR-0011 amendment):
the documentation-sync pipeline's CR, its task text, and vendored copies of
the plugins its nodes run (rig-emit, wiki-lint, git-push).

The decision base: `maxFixes` is the template's own (owner-private
versioned content; the chart-era contract governed a public default and
retires at phase 4). Per-env divergence rides the field-wise instance
merge (instance wins).

`plugins/` are drift-guarded against the kernel at the pinned tag — the
task text byte-checked the same way.
