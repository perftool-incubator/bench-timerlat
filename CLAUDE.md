# Bench-timerlat

## Purpose
Scripts and configuration to run the rtla timerlat benchmark within the crucible framework. Measures operating system timer latency.

## Language
Bash — all scripts

## Key Files
| File | Purpose |
|------|---------|
| `rickshaw.json` | Rickshaw integration: client scripts, parameter transformations |
| `multiplex.json` | Parameter validation and presets for multiplex |
| `timerlat-base` | Base setup shared by other scripts |
| `timerlat-client` | Client-side benchmark execution |
| `timerlat-get-runtime` | Extracts runtime from command-line options |
| `timerlat-post-process` | Parses timerlat output into crucible metrics |
| `workshop.json` | Engine image build requirements |

## Conventions
- Primary branch is `main`
- Standard Bash modelines and 4-space indentation
