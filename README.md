# PIRA validation

Manual standard-hosted validation of reviewed public [PIRA](https://github.com/AlgebraLoveme/PIRA) source.

This clean seed contains tooling and documentation only, not source snapshots, logs or copied Git history. The workflow is manual-only; pushes never request validation. The seed branch lacks a snapshot manifest and cannot pass the initial integrity gate.

Use the current clean public PIRA checkout and follow [the snapshot guide](tools/build/PRIVATE_CI.md): stage-public, inspect, then publish-public to an unused snapshot branch. Dispatch that branch once only after approval, selecting affected tools; inspect existing results before requesting more work. Final native x86/platform and reproducibility gates remain required.

The helper is mirrored here for reference; execute source staging from the canonical PIRA checkout.
