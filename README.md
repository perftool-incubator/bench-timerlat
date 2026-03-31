# bench-timerlat

Scripts and configuration to run the [rtla timerlat](https://docs.kernel.org/tools/rtla/rtla-timerlat.html) benchmark within the [crucible](https://github.com/perftool-incubator/crucible) performance testing framework. Measures operating system timer latency.

## Key Files

| File | Purpose |
|------|---------|
| `rickshaw.json` | Rickshaw integration: defines client scripts and parameter transformations |
| `multiplex.json` | Parameter validation and presets for multiplex |
| `timerlat-base` | Base setup shared by other scripts |
| `timerlat-client` | Client-side benchmark execution |
| `timerlat-get-runtime` | Runtime extraction |
| `timerlat-post-process` | Post-processing: parses timerlat output into crucible metrics |
| `workshop.json` | Engine image build requirements |
