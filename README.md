# contract-lbfgsb

L-BFGS-B written in Lean and emitted through Slang to CPU and SPIR-V, with the guest driver that drape, cage refit and head fitting share.

## What it is for

The Lean package defines the bounded quasi-Newton solver's kernels and emits them, and the C++ driver in `guest/` runs them on the CPU or on the GPU inside a sandbox guest. Host-native tests compare the driver with a reference implementation's fixtures. It finds the repositories it builds against as sibling checkouts at their goal-manifest paths, and `transport-meshing-pen` builds the guest programs.

## Build and run

    cd lean && lake build

## Licence

MIT. See [LICENSE](LICENSE).
