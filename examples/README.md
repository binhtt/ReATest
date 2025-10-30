# Examples for ReATest

This folder provides sample Rego policies and their corresponding test cases used in the evaluation.

## Included Examples

| Policy | Description | Test file |
|:--|:--|:--|
| `allow-privilege-escalation.rego` | Disallows privilege escalation in Kubernetes containers. | `allow-privilege-escalation.json` |
| `capabilities.rego` | Validates container Linux capabilities. | `capabilities.json` |
| `host-filesystem.rego` | Ensures host filesystem mounts are restricted. | `host-filesystem.json` |
| `host-namespaces.rego` | Restricts sharing of host namespaces. | `host-namespaces.json` |
| `privileged-containers.rego` | Detects containers running in privileged mode. | `privileged-containers.json` |
| `restricted-volumes.rego` | Restricts volume types allowed in pods. | `restricted-volumes.json` |
| `seccomp.rego` | Enforces valid seccomp profiles for containers. | `seccomp.json` |

