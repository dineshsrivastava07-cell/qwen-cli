# Qwen CLI - Always Active & Live

**Production-Ready Qwen CLI Configuration with Intelligent Expert Skill**

---

## Overview

This repository contains my personal **Qwen CLI** setup with:
- ✓ Always-active CLI configuration
- ✓ Qwen-native settings (NO Anthropic/Claude)
- ✓ Intelligent Expert Skill for production development
- ✓ MCP Server integration
- ✓ Cybersecurity expertise (OSCP grade)
- ✓ Enterprise-grade DevOps & automation

---

## Features

| Feature | Status |
|---------|--------|
| Keep-Alive | ✓ ENABLED |
| Stream Mode | ✓ ENABLED |
| Cache & Prefetch | ✓ ENABLED |
| Intelligent Expert Skill | ✓ ACTIVE |
| MCP Server | ✓ CONFIGURED |
| Security Level | ✓ ENTERPRISE |

---

## Quick Commands

```bash
# Wake up Qwen CLI
qp              # Ping - shows "Qwen: ALIVE ✓"
qs              # Full status display
qss             # Skill status
qsk             # Load Intelligent Expert skill

# Run Qwen commands
q "your prompt"
qwen "your prompt"
```

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/dineshsrivastava07-cell/qwen-cli.git ~/qwen-cli
cd ~/qwen-cli
```

### 2. Install MCP Server

```bash
cd ~/qwen-cli/mcp-server
npm install
npm run build
```

### 3. Copy Configuration

```bash
# Copy Qwen settings
cp ~/.qwen/skills/qwen-intelligent-expert/SKILL.md ~/.qwen/skills/

# Copy shell configuration
cat >> ~/.zshrc << 'EOF'

# Qwen CLI Configuration from qwen-cli repo
export QWEN_MODEL="qwen-max"
export QWEN_TEMPERATURE="0.7"
export QWEN_MAX_TOKENS="4096"
export QWEN_TIMEOUT="60000"
export QWEN_STREAM="true"
export QWEN_KEEP_ALIVE="true"
export QWEN_HEARTBEAT_INTERVAL="30"
export QWEN_CACHE_ENABLED="true"
export QWEN_PREFETCH="true"
export QWEN_SKILL="intelligent-expert"
export QWEN_SKILL_VERSION="1.0.0"
export QWEN_MODE="production-ready"
export QWEN_SECURITY_LEVEL="enterprise"
EOF

# Reload shell
source ~/.zshrc
```

### 4. Verify Installation

```bash
qss     # Should show "READY FOR PRODUCTION"
qp      # Should show "Qwen: ALIVE ✓"
```

---

## Configuration Files

| File | Purpose |
|------|---------|
| `~/.zshrc` | Shell configuration with Qwen aliases |
| `~/.qwen/skills/qwen-intelligent-expert/` | Intelligent Expert Skill |
| `~/qwen-cli/mcp-server/` | MCP Server for tool integration |

---

## Shell Aliases

| Alias | Command | Description |
|-------|---------|-------------|
| `q` | `qwen` | Quick Qwen command |
| `qs` | `qwen-status` | Full Qwen status |
| `qp` | `qwen-ping` | Instant ALIVE check |
| `qss` | `qwen-skill-status` | Skill status |
| `qsk` | `qwen-skill-load` | Load skill |

---

## Intelligent Expert Skill Capabilities

- **AI/ML**: Agent development, Chatbot architecture, RAG systems, LLM integration
- **Applications**: Full-stack development, Database design, UI/UX
- **Automation**: RPA agents, Workflow orchestration
- **DevOps**: CI/CD pipelines, Cloud architecture, Deployment
- **Security**: OSCP-grade, VA/PT, SOC analysis, Red/Blue/Orange team
- **Tools**: Kali Linux components and tools expertise

---

## Mandate

⚠️ **This configuration uses QWEN exclusively.**

- **NO** Anthropic/Claude settings
- **NO** External AI dependencies (unless explicitly required)
- **YES** Qwen-native implementations
- **YES** Local-first architecture where possible

---

## MCP Server

The MCP (Model Context Protocol) server provides:
- Tool integration for Qwen CLI
- Extended capabilities for AI agents
- Custom function calling
- Resource management

**Location**: `~/qwen-cli/mcp-server/`

**Start MCP Server**:
```bash
cd ~/qwen-cli/mcp-server
npm start
```

---

## Troubleshooting

### CLI Goes Idle/Unresponsive

1. Press `Ctrl+C` — cancel any stuck process
2. Run `qp` — verify Qwen is alive
3. Run `source ~/.zshrc` — reload configuration

### Skill Not Loading

```bash
qsk     # Load skill manually
qss     # Check skill status
```

---

## Author

- **GitHub**: [@dineshsrivastava07-cell](https://github.com/dineshsrivastava07-cell)
- **Email**: dinesh.srivastava07@gmail.com

---

## License

Personal configuration — feel free to use and adapt.

---

**Last Updated**: 2026-02-24  
**Version**: 1.0.0  
**Status**: Production-Ready ✓
