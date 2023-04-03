This repository is for deploying [Gatekeeper][], part of the Open Policy Agent project. GateKeeper provides support for both the validation and mutation of Kubernetes resources according to specific policies.

There are two applications contained in this repository:

- [`gatekeeper-system`](gatekeeper-system) deploys the GateKeeper service itself.
- [`policy`](policy) contains our policy definitions.

[gatekeeper]: https://open-policy-agent.github.io/gatekeeper/website/docs/
