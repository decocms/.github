<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/d3e36c98-4609-46d3-b39f-7ee1c6d77432">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/d3e36c98-4609-46d3-b39f-7ee1c6d77432">
  <img alt="decoCMS" src="https://github.com/user-attachments/assets/d3e36c98-4609-46d3-b39f-7ee1c6d77432">
</picture>

<h1 align="center">Context Management for AI-Native Operations</h1>

<p align="center">
<strong>Turn scattered AI experiments into production systems<br/>by making context infrastructure a first-class layer.</strong>
</p>

<p align="center">
<a href="https://decocms.com/mcp-mesh">MCP Mesh</a> · 
<a href="https://decocms.com/mcp-studio">MCP Studio</a> · 
<a href="https://docs.deco.page">Docs</a> · 
<a href="https://decocms.com/discord">Discord</a>
</p>

---

## What tends to break when AI moves past pilots

Your teams are building impressive AI demos in Lovable, Replit, and n8n. But they never reach production. The challenge is operating agents reliably as usage spreads across teams, environments, and tool surfaces.

**Why?** 

- **Governance gaps** — no consistent place to enforce SSO/RBAC, approvals, or audit trails  
- **Integration sprawl** - every client wires every tool with its own config, retries, and auth
- **Operational blind spots** - debugging is slow, costs are hard to attribute, and failures are hard to trace end-to-end
- **Context Obesity** — Bloated, expensive prompts delivering confused answers  

When those problems aren’t solved, teams either stall (over-centralize) or sprawl (ship shadow AI). Agents hallucinate because they lack unified access to enterprise data. IT locks down access because they lack visibility into what AI is doing.

---

## What deco CMS is

**deco CMS** is an open-source Context Management System for platform teams. 

It gives you:
- a production control plane for MCP traffic (connect, govern, observe)
- a path to package durable, reusable capabilities (so teams stop reinventing the same “agent”)
- a way to distribute what works safely across teams over time

---

## The platform 

<table>
<tr>
<td width="33%" valign="top">

### MCP Mesh
**Foundation**

One secure endpoint for every MCP server. Route, govern, observe and optimize MCP traffic with policy enforcement, audit trails, and multiple runtime strategies.

[**Explore MCP Mesh →**](https://github.com/decocms/mesh)

</td>
<td width="33%" valign="top">

### MCP Studio
**Development**

No-code admin + SDK to package MCP capabilities as reusable building blocks. Turn tools + schemas + workflows into apps with consistent interfaces and permissions. 

[**Get Early Access →**](https://decocms.com/mcp-studio)

</td>
<td width="33%" valign="top">

### MCP Apps & Store
**Distribution**

Marketplace for composing, consuming, and (eventually) monetizing MCP apps.

[**Coming Soon**](https://decocms.com)

</td>
</tr>
</table>

---

## Why MCP?

We're built on the [Model Context Protocol](https://modelcontextprotocol.io) because enterprises need interoperability at the tool layer, and a way to operate that tool access with the same rigor as any other production surface.

MCP gives you a standard interface. deco CMS provides the control plane around it:

- **Portable** — Self-host on Kubernetes, deploy on-prem, or use our cloud (coming soon)
- **Composable** — swap models, swap MCP servers, adopt community tools, build your own  
- **Auditable** — centralized policies, logs, and traces across tool + model calls  
- **No lock-in** — Your context, your infrastructure. Audit the code, fork if needed

---

## Quick Start

```bash
npx @decocms/mesh init
```

→ One command spins up a local MCP Mesh so you can connect MCP servers and test with MCP clients

---

## Category: Context Management

Most AI efforts optimize prompts. AI-native companies optimize **context**.

Better context produces better outputs — and outcomes create new context (feedback, policies, routing decisions, and reusable components).

deco CMS is built for that loop: instrument every call, learn what works, and improve routing, retrieval, execution over time.

---

## Links

| | |
|---|---|
| 📘 **Documentation** | [docs.deco.page](https://docs.deco.page) |
| 💬 **Community** | [Discord](https://decocms.com/discord) |
| 🌐 **Website** | [decocms.com](https://decocms.com) |
---

<sub>Made with ❤️ by the deco community</sub>
</div>
