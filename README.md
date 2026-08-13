# dea-catalog-signals

> DEA catalog for **Signal** — OpenDEAM v0.3.0 (ADR-0003).

## Signal (`SIG`)

- **Entity id:** `dea:entity-signal`
- **Allocation:** L2 · L2-innovation-foresight
- **Status:** proposed

A weak or early indicator of environmental change (market, technology, regulatory, competitive) worth tracking before it forces adaptation.

## Relationships (from the OpenDEAM model)

- **SIG → EXP** — triggers (dependency, 0..N:0..N)

## Allocation contract

This repo's `metamodel-pointer.yaml` is validated in CI against the pinned
OpenDEAM root model (`v0.3.0`) via the reusable
`validate-against-model.yml` workflow. Drift fails CI.

Content (entity instances) lands when the entity promotes from
`proposed` to `planned`/`scaffold` per the model lifecycle.

## License

Apache 2.0 — see [LICENSE](./LICENSE) and [NOTICE](./NOTICE).
