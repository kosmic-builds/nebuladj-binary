# NebulaDJ releases repository.

NebulaDJ is DJ software that can be automated by AI agents via MCP and the app specific DSL.

Version 1.5.2 trade-offs:
- Relies on your existing tags: key and BPM are read from Mixed In Key tags and never detected. Untagged tracks show no key, and BPM is used only as a hint for the beat grid.
- Not signed by Apple: there is no Developer ID, so the first launch needs a one-time “Open Anyway”. Updates come from GitHub releases.
