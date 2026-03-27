# LAIRCA Logos Christian Theological Model

A fractal, machine-readable theological parent model for LAIRCA, built as a sister repository to the AIRCA Fractal Decision Architecture project.

## Why this repo exists

The AIRCA repository provides the operational decision architecture. This repository provides the upstream Christian theological architecture that can instantiate the U-layer as LAIRCA.

In plain terms:

- **AIRCA repo** = decision operating architecture
- **This repo** = theological source architecture, doctrinal ordering, weighting logic, and derivation chains for the Christian instantiation of that architecture
- **Habitat applications** = downstream institutional use case derived from this theological parent model

This repo is intentionally separate so the AIRCA project stays operationally clean while the Christian theological source layer remains rigorous, inspectable, extensible, and modular.

## Companion relationship

Primary companion repository:
- `https://github.com/lowelltwong-alt/airca-fractal-decision-architecture`

This repository is connected to the AIRCA repo through:
- mirrored root structure
- mirrored node-level artifact pattern
- shared fractal artifact logic
- crosswalk documents under `docs/integrations/lairca/`
- common machine-readable artifact style
- explicit lineage and derivation references

## Core design rules

1. Keep the recursive shell fixed.
2. Model new things as nodes first.
3. Treat doctrines as stable objects.
4. Treat ordering and weighting as configurable interpretive layers.
5. Preserve lineage, lifecycle, and approval logic at every meaningful level.
6. Do not let blank fields imply destructive permissions.
7. Keep the Christian core broad enough for orthodox reuse, with optional overlays for narrower traditions.

## Root architecture

- `docs/canon/` for theologian and source canon
- `docs/doctrines/` for doctrinal nodes
- `docs/orderings/` for lens stacks and alternative orders
- `docs/weightings/` for explicit priority logic
- `docs/derivations/` for theology -> ethics -> governance -> LAIRCA -> application chains
- `docs/lairca/` for the explicit Christian instantiation layer
- `docs/integrations/` for AIRCA, Habitat, AI ethics, and institutional governance crosswalks
- `schemas/` for node templates and controlled vocabularies
- `registry/` for reusable indexes
- `examples/` for worked derivation examples

## Recommended default theological core

The root canon in this scaffold emphasizes a broad orthodox core rather than a narrow modern substream. Starter canon includes:

- Augustine
- Athanasius
- Irenaeus
- Thomas Aquinas
- John Calvin
- Herman Bavinck
- Abraham Kuyper
- J.I. Packer
- R.C. Sproul
- Tim Keller
- John Stott
- Francis Schaeffer
- Dallas Willard
- Henri Nouwen
- Oliver O'Donovan

Extension voices may include:
- Jonathan Edwards
- C.S. Lewis
- Lesslie Newbigin
- John Piper
- Wayne Grudem
- N.T. Wright

MacArthur is intentionally excluded from the shared core and may be added as a local optional module by users who want that overlay.

## Ordering logic

This repo assumes theology should not only be listed. It should be orderable and weightable.

So the structure distinguishes:
- **doctrine nodes**: stable theological objects
- **ordering profiles**: candidate sequences for evaluation
- **weighting profiles**: relative importance or force in a use case
- **application selections**: the ordering chosen for a specific institution or decision context

## Fractal node pattern

Each major node can evolve toward a repeated internal structure:
- `README.md`
- `artifact.json`
- `sources-and-lineage.md`
- `notes.md`
- `examples.md`
- optional schemas or sidecars

## Connected use

This repo is meant to be interrogated by AI, reviewed by humans, and used as an upstream interpretive architecture for LAIRCA and downstream applications such as Habitat for Humanity strategy, nonprofit governance, Christian AI ethics, and institution-specific translation layers.

## First steps

1. Read `docs/lairca/README.md`
2. Read `docs/integrations/lairca/airca-companion-crosswalk.md`
3. Read `docs/orderings/README.md`
4. Read `docs/derivations/README.md`
5. Start filling out canon and doctrine nodes using the schemas in `schemas/`

## Attribution

Author attribution should appear as **Lowell T. Wong**.
