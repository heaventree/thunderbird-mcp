# Pinned fork

This fork is pinned to upstream `TKasperczyk/thunderbird-mcp` commit `8910dbf` (v0.10.0), which was reviewed before use.

Change from upstream: `update_url` is removed from `extension/manifest.json`, so installed copies never auto-update from the maintainer's domain. Updates are manual: review the upstream diff, then merge it here.

`dist/thunderbird-mcp.xpi` is the upstream v0.10.0 XPI with only that manifest line removed. Its sha256 is `13d84678767de227919f2752c0f5266b150b41f1baa69a919ec6d627b3f3dcd2`.
