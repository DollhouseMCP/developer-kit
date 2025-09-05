# DollhouseMCP - MCP Client Compatibility Matrix

**Last Updated**: September 5, 2025  
**Data Version**: 1.0.0  
**Status**: Community Testing In Progress  
**Purpose**: Track DollhouseMCP compatibility across major MCP clients  
**Total MCP Clients Available**: 378+ ([Full Directory](https://www.pulsemcp.com/clients))  
**MCP Protocol Version**: 1.0.3 (as of September 2025)

## Related Documentation
- [RAPPEL Framework Comparison](frameworks/RAPPEL_FRAMEWORK_DOLLHOUSEMCP.md) - How DollhouseMCP aligns with industry frameworks
- [Complete Client Listing](MCP_CLIENT_FULL_LISTING.md) - Full 378+ client enumeration and testing roadmap

---

## Compatibility Legend

- ✅ **Full Support** - All DollhouseMCP features work as expected
- ⚡ **Enhanced** - Has unique/special features on this platform
- ⚠️ **Partial** - Some features work, some limitations
- ❌ **Not Working** - Significant issues or incompatibilities
- 🔄 **Testing** - Currently being evaluated
- ❓ **Unknown** - Not yet tested

---

## Primary AI Platforms

| Client | Status | Personas | Skills | Templates | Agents | Memory | Notes |
|--------|--------|----------|--------|-----------|--------|--------|-------|
| **Claude Desktop** | ✅ | ✅ | ✅ | ✅ | ⚠️ | ✅ | Sandbox environment, some agent limitations |
| **Claude Code** | ⚡ | ✅ | ⚡ | ✅ | ✅ | ✅ | Enhanced: Full filesystem access, terminal control |
| **ChatGPT Desktop** | ✅ | ✅ | ✅ | ✅ | 🔄 | 🔄 | Native support since March 2025 |
| **Google Gemini** | ✅ | ✅ | ✅ | ✅ | 🔄 | 🔄 | Via Vertex AI or direct API |
| **VS Code Copilot** | ⚡ | ✅ | ⚡ | ✅ | ✅ | ✅ | Enhanced: IDE-specific skills work better |

---

## Development IDEs & Editors

| Client | Status | Personas | Skills | Templates | Agents | Memory | Special Features |
|--------|--------|----------|--------|-----------|--------|--------|------------------|
| **Cursor IDE** | ⚡ | ✅ | ⚡ | ✅ | ✅ | ✅ | Multi-file editing, codebase awareness |
| **Windsurf** | ✅ | ✅ | ✅ | ✅ | 🔄 | ✅ | Gemini 2.5 default, Claude via API |
| **Continue** | ⚡ | ✅ | ⚡ | ✅ | ⚠️ | ✅ | VS Code + JetBrains support |
| **Cline** | ⚡ | ✅ | ⚡ | ✅ | ✅ | ✅ | Autonomous agent capabilities |
| **Zed** | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | Testing in progress |
| **Replit** | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | Cloud IDE considerations |

---

## Terminal & Command Line

| Client | Status | Personas | Skills | Templates | Agents | Memory | Special Notes |
|--------|--------|----------|--------|-----------|--------|--------|---------------|
| **Warp Terminal** | ⚡ | ✅ | ⚡ | ✅ | ⚠️ | ✅ | Terminal-specific skills enhanced |
| **MCP-CLI** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | Reference implementation |
| **Dolphin MCP** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | Multi-server bridge |
| **mcp-use** | ⚠️ | ⚠️ | ✅ | ⚠️ | ❌ | ⚠️ | Free alternative, basic features |

---

## Local Model Platforms

| Client | Status | Personas | Skills | Templates | Agents | Memory | Unique Aspects |
|--------|--------|----------|--------|-----------|--------|--------|----------------|
| **Ollama** | ✅ | ✅ | ✅ | ✅ | ⚠️ | ⚠️ | Model-dependent, needs function calling |
| **LM Studio** | ⚡ | ✅ | ✅ | ✅ | 🔄 | ⚡ | Multi-model: Can share MCP across models! |
| **LocalAI** | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | Testing needed |
| **Jan.ai** | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | Testing needed |

---

## Chat Clients

| Client | Status | Personas | Skills | Templates | Agents | Memory | Notes |
|--------|--------|----------|--------|-----------|--------|--------|-------|
| **LibreChat** | ✅ | ✅ | ✅ | ✅ | ⚠️ | ✅ | Open source, multi-provider |
| **5ire** | ✅ | ✅ | ✅ | ✅ | ❓ | ✅ | Beginner-friendly |
| **AIaW** | ✅ | ✅ | ✅ | ✅ | ❓ | ✅ | Lightweight |
| **DeepChat** | ✅ | ✅ | ✅ | ✅ | ❓ | ✅ | Privacy-focused |
| **ChatMCP** | ✅ | ✅ | ✅ | ✅ | ❓ | ✅ | Web-based |
| **CarrotAI** | ✅ | ✅ | ✅ | ✅ | ❓ | ✅ | Multi-language UI |
| **Cherry Studio** | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | Testing needed |
| **NextChat** | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | Testing needed |

---

## Specialized/Workflow Tools

| Client | Status | Personas | Skills | Templates | Agents | Memory | Unique Use Cases |
|--------|--------|----------|--------|-----------|--------|--------|------------------|
| **n8n** | ⚡ | ⚠️ | ⚡ | ✅ | ⚡ | ✅ | Workflow automation, trigger-based skills |
| **Home Assistant** | ⚡ | ⚠️ | ⚡ | ⚠️ | ⚡ | ✅ | Home automation personas/skills |
| **Zapier AI** | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | If MCP support added |
| **Make.com** | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | If MCP support added |

---

## Scientific/Research Tools

| Client | Status | Personas | Skills | Templates | Agents | Memory | Domain-Specific Features |
|--------|--------|----------|--------|-----------|--------|--------|--------------------------|
| **Perplexus** | ⚡ | ✅ | ⚡ | ✅ | ❓ | ❓ | Chemistry-specific skills enhanced |
| **Jupyter + MCP** | ⚡ | ✅ | ⚡ | ✅ | ⚠️ | ✅ | Data science personas excel here |
| **CoCalc** | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | Collaborative computation |

---

## Enterprise Platforms

| Client | Status | Personas | Skills | Templates | Agents | Memory | Enterprise Features |
|--------|--------|----------|--------|-----------|--------|--------|---------------------|
| **Microsoft Copilot Studio** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | One-click MCP setup |
| **Azure OpenAI + MCP** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | Via MCP integration |
| **Vertex AI** | ✅ | ✅ | ✅ | ✅ | 🔄 | 🔄 | Google Cloud integration |
| **AWS Bedrock + MCP** | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | 🔄 | Testing needed |

---

## Mobile Clients

| Client | Status | Personas | Skills | Templates | Agents | Memory | Mobile Limitations |
|--------|--------|----------|--------|-----------|--------|--------|--------------------|
| **BoltAI Mobile** | ✅ | ✅ | ⚠️ | ✅ | ❌ | ✅ | Limited filesystem access |
| **Claude Mobile** | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | No MCP support yet |
| **ChatGPT Mobile** | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | No MCP support yet |

---

## Platform-Specific Considerations

### Unique Enhancements by Platform

#### **Claude Code** 
- Full filesystem access enables file-management skills
- Terminal access enables system-level skills
- Git integration works seamlessly

#### **VS Code / Cursor**
- Code-analysis skills have deeper integration
- Multi-file refactoring works better
- Debugging personas more effective

#### **n8n**
- Skills can be triggered by external events
- Workflow-based personas excel
- API integration skills enhanced

#### **LM Studio**
- **Unique**: Single MCP server can feed multiple models
- Changes in one model's context immediately available to others
- Potential for model-ensemble personas

#### **Home Assistant**
- IoT device control skills work
- Automation personas make sense
- Time-based templates useful

---

## Testing Checklist for New Platforms

When testing DollhouseMCP on a new MCP client:

### Basic Compatibility
- [ ] Can activate personas
- [ ] Personas persist across sessions
- [ ] Skills execute properly
- [ ] Templates render correctly
- [ ] File system access (if applicable)
- [ ] Network access (if applicable)

### Advanced Features
- [ ] Agents can complete multi-step tasks
- [ ] Memory persists between sessions
- [ ] Cross-element references work
- [ ] Custom tools can be added
- [ ] Performance is acceptable

### Platform-Specific
- [ ] Identify unique capabilities
- [ ] Document special use cases
- [ ] Note any limitations
- [ ] Find killer feature combinations

---

## Contributing

To add or update compatibility information:

1. Test DollhouseMCP with the client
2. Document your findings
3. Submit a PR with updates to this matrix
4. Include:
   - Client version tested
   - Date of testing
   - Specific features that work/don't work
   - Any workarounds discovered

---

## Additional Clients to Test

From the 378+ total MCP clients, here are additional ones for community testing:

### AI Development Tools
- GenAIScript, Smolagents, TinyAgents, Metis Router, AgentGraph

### Communication/Chat
- Slack Assistant, Lark (Feishu), Xiaohongshu, HyperChat, SeekChat

### Code Editors & IDEs  
- OpenCode, Roo Code, MCPHub.nvim, mcp.el (GNU Emacs), chat.md

### Terminal/CLI Tools
- Oterm, Amazon Q Developer CLI, Y CLI, Groq Desktop

### Specialized Tools
- GHOSTCREW (Cybersecurity), Trading Agents, Recipe Manager, Home Assistant (Xiaozhi AI)
- QU3 (Quantum-Safe), Real Estate AI Agent, RAG with AWS Bedrock

### Testing/Development
- MCP Client Tester, Inspector, CLI Inspector, MCPJam Inspector, Protolint

### Mobile/Desktop Apps
- Jan, UI-TARS Desktop, DeskAid, Witsy, Evo AI

### Framework Integrations
- LangChain.js Adapters, Langgraph Tools, Dify Plugin Agent, Vue Chat Interface

---

## Community Testing Program

We need help testing DollhouseMCP with all 378+ clients! 

### How to Contribute:
1. Pick any untested client from [PulseMCP Directory](https://www.pulsemcp.com/clients)
2. Install DollhouseMCP on that client
3. Run through the testing checklist
4. Report results via GitHub Issue or PR

### Priority Testing Targets:
- Top 30 featured clients on PulseMCP
- Enterprise tools (AWS Bedrock, Azure, GCP integrations)
- Popular open-source clients
- Domain-specific tools (science, finance, automation)

---

## Resources

- [Full MCP Clients Directory](https://www.pulsemcp.com/clients) - Complete list of 378+ clients
- [Official MCP Clients](https://modelcontextprotocol.io/clients)
- [Awesome MCP Clients](https://github.com/punkpeye/awesome-mcp-clients)
- [MCP Wikipedia](https://en.wikipedia.org/wiki/Model_Context_Protocol)

---

## Notes

- This is a living document - compatibility may change as clients update
- Some features may work differently than expected on certain platforms
- Platform-specific skills and personas can provide unique value
- Multi-model platforms (like LM Studio) offer unique orchestration possibilities

---

*Last major review: September 4, 2025*  
*Next scheduled review: October 1, 2025*