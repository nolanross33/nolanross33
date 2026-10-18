### Hi, I'm Nolan

Presales/Solutions Engineer in cybersecurity (CISSP, CCSK) with a background
that runs IT generalist → detection engineering → observability → presales SE.
I learn by building — most of what's pinned here came out of a home lab
rather than a classroom, because that's what actually sticks.

#### 🔭 What I've got

- **An ever-growing home lab...** ESXi host running a full NetWitness
  (network detection & response) deployment, UniFi networking with VLAN
  segmentation, and a few k3s clusters I use to sandbox and test things.
- **Agent tooling for security data.** Built an MCP server that exposes my 
  NetWitness session/alert/incident data as structured tools for an LLM
  agent, wired into Docker's MCP Gateway. Less "wrap an API," more "figure
  out what an agent actually needs to reason well about detection data."

#### 🌱 Technical domains

`Terraform` · `Kubernetes (k3s)` · `Python` · `Docker` · `MCP (Model Context
Protocol) servers` · `NetWitness / network detection & response` · `UniFi
networking & VLAN segmentation` · `IAM` (OneLogin, JumpCloud) · `vSphere/ESXi`

#### 📌 Pinned

- **[homelab-iac](https://github.com/nolanross33/homelab-iac)** — Terraform
  (vSphere provider) provisioning k3s nodes on my ESXi host, then RBAC,
  NetworkPolicies, and Secrets on the resulting cluster. Structured as a
  learning sequence, not just a config dump.
- **[nw-homelab-mcp-server](https://github.com/nolanross33/nw-homelab-mcp-server)**
  — Dockerized MCP server exposing 9 tools for querying NetWitness sessions,
  alerts, and incidents from an LLM agent.

#### 📫 Reach out

Open to connecting — feel free to open an issue on any repo above.
