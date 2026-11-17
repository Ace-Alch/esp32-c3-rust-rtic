# ESP32-C3 Rust and RTIC Experiments: validation

## Current evidence

This documentation update inspected available text and file inventories. It did not execute the project, simulate a model or test hardware. Existing recorded results must be cited with their original conditions.

## Proposed checks

These are test plans. No row below is marked as passed.

| Check | Action | Evidence to retain | Status |
| :-- | :-- | :-- | :-- |
| V01: Button events | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |
| V02: Interrupt handling | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |
| V03: Rhythm timing | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |
| V04: RGB output | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |

## Project-specific checks

- Verify or recover: Cargo manifest and lockfile.
- Verify or recover: Board pinout.
- Verify or recover: Toolchain and target.
- Verify or recover: Measured interrupt behavior.

## Reporting rule

Report units, sample size, configuration, error bounds and failures. Separate a simulation result from a hardware result. Separate an emulator check from a physical-device check. A screenshot alone does not establish numerical accuracy.
