# ontology-template agent guidance

This repository is the starting point for a new ontology package: a TypeQL package built on gist.

Before changing or releasing this package (or one made from it), follow the `ontology-extend`
skill: questions first, design on gist, version bump, the three install tests, `ont release`.

Agent skills come from the vibe-machine skill cabinet through `apm.yml`. Run `apm install` to
refresh them; never edit `.claude/skills/` or `.agents/skills/` by hand.
