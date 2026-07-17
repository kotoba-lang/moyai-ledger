# Moyai ledger shared-library rules

- `library.edn` is canonical repository metadata.
- Preserve append-only monotone epochs, non-monetary credit, non-transferability, decay,
  conservation, and the governance/benefit firewalls.
- Do not add transfer, gift, merge, pool, cash redemption, governance weight, or benefit gates.
- Keep the implementation actor-neutral and free of root-relative dependencies.
- Run `./run_tests.sh` before committing.
