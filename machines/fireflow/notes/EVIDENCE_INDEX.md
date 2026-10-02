# Fireflow — Evidence Index

The screenshots captured during the Fireflow solve were reviewed, renamed by attack stage, and sanitized before publication.

| Asset | Walkthrough Section | Purpose | Publication Status |
|---|---|---|---|
| `assets/01-nmap-enumeration.webp` | 1.1 | Nmap service and TLS enumeration | Prepared |
| `assets/02-tls-san-hostnames.webp` | 1.1 | Certificate CN/SAN hostname discovery | Prepared |
| `assets/03-fireflow-https-headers.webp` | 1.1 | HTTPS hostname-routing behavior | Prepared |
| `assets/04-flow-playground-url.webp` | 1.2 | Open Agent redirect and public flow identifier | Prepared |
| `assets/05-langflow-playground.webp` | 1.2 | Langflow playground interface | Prepared |
| `assets/06-host-resolution-fix.webp` | 1.2 | Local hostname resolution | Prepared |
| `assets/07-langflow-version.webp` | 2 | Langflow version fingerprint | Prepared |
| `assets/08-cve-poc-clone.webp` | 3 | Initial exploit preparation | Prepared |
| `assets/09-cve-exploit-attempt.webp` | 3 | Exploit execution | Prepared |
| `assets/10-www-data-shell.webp` | 3 | Reverse shell as `www-data` | Prepared |
| `assets/11-cve-request-timeout.webp` | 3 | Callback troubleshooting | Prepared |
| `assets/12-langflow-environment-redacted.webp` | 4 | Langflow process environment | **Redacted** |
| `assets/13-nightfall-account.webp` | 4 | Local account discovery | Prepared |
| `assets/14-nightfall-home-enumeration.webp` | 5 | Nightfall home enumeration | Prepared |
| `assets/15-mcp-config-redacted.webp` | 6.1 | MCP configuration | **Redacted** |
| `assets/16-user-flag-redacted.webp` | 5 | User proof | **Redacted** |
| `assets/17-jwt-auth-forgery-redacted.webp` | 6.1 | JWT authentication / authorization workflow | **Redacted** |
| `assets/18-mcp-tool-registration.webp` | 6.2 | MCP tool registration | Prepared |
| `assets/19-mcp-tool-call.webp` | 6.2 | MCP JSON-RPC tool invocation | Prepared |
| `assets/20-mcp-registration-http-200.webp` | 6.2 | Successful tool registration | Prepared |
| `assets/21-mcp-persistent-session-script.webp` | 6.2 | Persistent backend session / execution probe | Prepared |
| `assets/22-kubernetes-rbac-nodes-proxy.webp` | 6.3 | Kubernetes `nodes/proxy` RBAC | Prepared |
| `assets/23-root-flag-redacted.webp` | 6.3 | Final root proof | **Redacted** |

## Publication Rules

- Flags are redacted.
- Reusable credentials and application secret keys are redacted.
- JWTs and Kubernetes service-account tokens are redacted.
- Screenshots are named by attack stage rather than timestamp.
- Each image is placed immediately after the paragraph it supports in the walkthrough.
