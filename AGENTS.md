# Bench-timerlat

## Purpose
Scripts and configuration to run the rtla timerlat benchmark within the crucible framework. Measures operating system timer latency on isolated CPU cores.

## Language
- Bash for client execution scripts
- Python for post-processing (`timerlat-post-process`)

## Key Files
| File | Purpose |
|------|---------|
| `rickshaw.json` | Rickshaw integration: client scripts, parameter transformations |
| `multiplex.json` | Parameter validation rules, unit conversions, and presets for multiplex |
| `benchmark-metadata.json` | Machine-readable description and CDM-indexed source/type list (consumed by `crucible benchmarks list`) |
| `timerlat-base` | Base setup shared by other scripts |
| `timerlat-client` | Client-side benchmark execution |
| `timerlat-get-runtime` | Extracts runtime from command-line options |
| `timerlat-post-process` | Parses timerlat output into crucible metrics |
| `workshop.json` | Engine image build requirements |

## Conventions
- Primary branch is `main`
- Standard Bash modelines and 4-space indentation
- Python code follows 4-space indentation with standard modelines
