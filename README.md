# 💪 resilienceOracle

**DORA Execution MCP Server** — 10 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-10-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Enterprise-FF6D00?style=flat-square)
![Bus](https://img.shields.io/badge/Oracle_Bus-Connected-00C853?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/resilience/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "resilienceoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/resilience/mcp/"]
    }
  }
}
```

## Tools (10)

| Tool | Description |
|------|-------------|
| `register_system` | Register a business-critical ICT system for BCM tracking. |
| `set_bia` | Set Business Impact Analysis data — RTO, RPO, MTPD, financial impact. |
| `rto_rpo_check` | Validate RTO/RPO targets against actual backup/failover capabilities. |
| `test_register` | Register a DR/BCM test execution with results and evidence. |
| `scenario_library` | DORA-relevant test scenario library (10 scenarios). |
| `bcm_gap_analysis` | BCM plan completeness analysis across all systems. |
| `recovery_status` | Recovery readiness dashboard — how many systems are DR-ready. |
| `crisis_plan_check` | Validate crisis communication plan elements (Art. 11(7)). |
| `evidence_bundle` | Collect BCM/DRP evidence for audit — systems, BIA, test records. |
| `health_check` | Server status. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 10 calls/day | €0 |
| Pro | 1,000 calls/day | €99/month |
| Enterprise | Unlimited | Custom |

> **Note:** This is a compliance oracle. Full tool access requires a Pro or Enterprise subscription. Free tier includes read-only assessment tools.

## Part of ToolOracle

resilienceOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.

### DORA Coverage

**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/resilience/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
