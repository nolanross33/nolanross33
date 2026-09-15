### Hi, I'm Nolan

Presales/Solutions Engineer in cybersecurity (CISSP, CCSK) with a background
that runs IT generalist → detection engineering → observability → presales SE.
I learn by building — most of what's pinned here came out of a home lab
rather than a classroom, because that's what actually sticks.

#### 🔭 What I'm working on

- **A real home lab, not a demo one.** ESXi host running a full NetWitness
  (network detection & response) deployment, UniFi networking with VLAN
  segmentation, and now a Terraform + k3s cluster layered on top — the same
  hardware serves both "detection engineering sandbox" and "IaC practice
  environment."
- **Agent tooling for security data.** Built an MCP server that exposes my 
  NetWitness session/alert/incident data as structured tools for an LLM
  agent, wired into Docker's MCP Gateway. Less "wrap an API," more "figure
  out what an agent actually needs to reason well about detection data."

#### 🌱 Technical domains

`Terraform` · `Kubernetes (k3s)` · `Python` · `Docker` · `MCP (Model Context
Protocol) servers` · `NetWitness / network detection & response` · `UniFi
networking & VLAN segmentation` · `IAM` (OneLogin, JumpCloud) · `vSphere/ESXi`

#### 💭 How I think about this

RBAC, network segmentation, and least-privilege aren't new concepts to me —
they're just IAM and detection-engineering thinking wearing a Kubernetes or
Terraform costume. I'd rather spend the extra hour understanding *why*
something is architected a certain way than memorize the syntax that makes
it run. That's also why the repos below have more comments than the average
homelab project — they're written the way I'd want to hand something off in
a presales technical validation.

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
