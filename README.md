This repository is for deploying [Gatekeeper][], part of the Open Policy Agent project. GateKeeper provides support for both the validation and mutation of Kubernetes resources according to specific policies.

There are two applications contained in this repository:

- [`gatekeeper-system`](gatekeeper-system) deploys the GateKeeper service itself.
- [`policy`](policy) contains our policy definitions.

[gatekeeper]: https://open-policy-agent.github.io/gatekeeper/website/docs/

NB: We see errors like this in the gatekeeper-controller-manager logs:

```
http: TLS handshake error from 10.128.0.1:52948: EOF
```

According to [open-policy-agent/gatekeeper#2142](https://github.com/open-policy-agent/gatekeeper/issues/2142), these messages are probably harmless.
