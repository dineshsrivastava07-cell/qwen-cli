# Qwen MCP Server

Production-ready MCP (Model Context Protocol) server for Qwen CLI providing intelligent expert capabilities.

## Features

### Development Tools
- **architecture_design** - End-to-end solution architecture
- **code_development** - Code, scripts, and system components
- **api_engineering** - API design and integrations
- **data_modelling** - Data models and algorithms
- **system_wiring** - Component integration
- **performance_optimization** - Performance and scalability

### Testing Tools
- **unit_testing** - Unit test creation
- **integration_testing** - Integration tests
- **debugging** - Error resolution

### Security Tools
- **secure_architecture** - Security-by-design
- **vulnerability_assessment** - VA/PT with Kali tools
- **soc_analysis** - SOC analysis
- **threat_modelling** - Threat modeling
- **digital_forensics** - Forensic analysis

### DevOps Tools
- **version_control** - Git management
- **build_automation** - CI pipelines
- **deployment** - Release management
- **monitoring** - System monitoring
- **observability** - Logging implementation
- **reliability_engineering** - SRE practices

## Installation

```bash
cd mcp-server
npm install
```

## Usage

### Run Server
```bash
npm start
```

### Development Mode
```bash
npm run dev
```

### Configure in Qwen CLI

Add to your Qwen settings:

```json
{
  "mcpServers": {
    "qwen-expert": {
      "command": "node",
      "args": ["/path/to/qwen-cli/mcp-server/src/index.js"],
      "env": {}
    }
  }
}
```

## Resources

The server provides these resources:
- `mcp://qwen/architecture-templates` - Architecture patterns
- `mcp://qwen/security-guidelines` - Security best practices
- `mcp://qwen/devops-pipelines` - CI/CD templates
- `mcp://qwen/testing-frameworks` - Testing guides
- `mcp://qwen/best-practices` - Enterprise practices

## Prompts

Available prompts:
- `architecture_review` - Review system architecture
- `security_assessment` - Security assessment
- `code_review` - Code quality review
- `incident_response` - Incident response guide

## License

MIT
