# HTB Machine Walkthroughs

A curated repository of **authorized Hack The Box walkthroughs** documenting methodology, tooling, exploitation paths, and security lessons learned during lab-based penetration testing.

## Machines

| Machine | OS | Difficulty | Core Themes | Status |
|---|---|---:|---|---|
| [Fireflow](machines/fireflow/README.md) | Linux | Medium | Langflow RCE, credential reuse, JWT alg:none, MCP, Kubernetes RBAC, kubelet | Completed |
| Paperwork | Linux | — | Private walkthrough | Private until machine retirement |

## Private / Unreleased Walkthroughs

**Paperwork** has been documented but is intentionally kept private while the machine remains active.

Its walkthrough files, screenshots, exploitation details, and Git history are not included in this public repository. The walkthrough may be published after the machine is retired.

## Repository Structure

~~~text
machines/
└── <machine>/
    ├── README.md
    ├── assets/
    ├── scans/
    ├── scripts/
    └── notes/
~~~

Each machine directory is self-contained.

## Documentation Standards

The walkthroughs are intended to be:

- **accurate** — based on commands and evidence captured during the actual solve
- **professional** — clear methodology and technical reasoning
- **publication-safe** — flags, passwords, private keys, tokens, VPN files, and reusable secrets are omitted or redacted
