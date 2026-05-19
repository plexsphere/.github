# Plexsphere

**The sovereign control plane between your ecosystem and any provider.**

> _Infrastructure you can't move is infrastructure you don't control._

Plexsphere is a multi-provider control plane that unifies heterogeneous
infrastructure — bare-metal, VMs, Kubernetes clusters, and edge devices, across
clouds and on-premises — into a single, coherent, provider-agnostic fabric.
It eliminates vendor lock-in by managing portable infrastructure through open
standards.

> ⚠️ **Status: Design / Draft.** APIs and the domain model will evolve as the
> platform matures through real-world deployments.

## What it does

- **Unified control plane** — one place for identity, policy, secrets, and
  mediated access across every provider.
- **Encrypted mesh** — a WireGuard mesh network connects all resources, split
  into distinct control, session, and data planes.
- **Hierarchical isolation** — a Domain → Project → Resource model keeps
  tenants and environments cleanly separated.
