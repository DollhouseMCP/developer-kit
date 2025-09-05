# Complete MCP Client Directory for DollhouseMCP

**Document Version**: 1.0.0  
**Last Updated**: September 5, 2025  
**Total Clients**: 378+ as of September 4, 2025  
**Source**: [PulseMCP Directory](https://www.pulsemcp.com/clients)  
**Purpose**: Document ALL MCP clients and their testing status with DollhouseMCP

## Related Documentation
- [MCP Client Compatibility Matrix](MCP_CLIENT_COMPATIBILITY_MATRIX.md) - Detailed testing status for priority platforms
- [RAPPEL Framework Implementation](frameworks/RAPPEL_FRAMEWORK_DOLLHOUSEMCP.md) - Using DollhouseMCP with industry frameworks

---

## Why This Document Exists

DollhouseMCP's value is that it works **everywhere MCP works**. We track all 378+ clients because:
- Every client represents potential users
- Some clients have unique capabilities that enhance DollhouseMCP
- Open source means supporting the entire ecosystem
- Community testing helps us discover edge cases

---

## Testing Priority System

### 🔴 **Tier 1: Detailed Tracking** (See MCP_CLIENT_COMPATIBILITY_MATRIX.md)
Why: High user volume, enterprise adoption, or unique features
- Claude Desktop/Code
- ChatGPT Desktop
- Google Gemini
- VS Code/GitHub Copilot
- Cursor IDE
- Windsurf
- Ollama
- LibreChat
- Microsoft Copilot Studio

### 🟡 **Tier 2: Category Tracking** 
Why: Similar functionality within category, test representatives
- IDE/Editor category (20+ clients)
- Chat UI category (30+ clients)
- Terminal/CLI category (15+ clients)
- Framework integrations (25+ clients)

### 🟢 **Tier 3: Community Tracking**
Why: Specialized use cases, lower volume, community-driven testing
- Domain-specific tools
- Experimental clients
- Personal projects
- Regional variants

---

## Complete Client Listing

### Featured Clients (Top 30 from PulseMCP)

| # | Client | Category | Testing Status | Why We Track |
|---|--------|----------|----------------|--------------|
| 1 | VS Code | IDE | ✅ Detailed | Major IDE, millions of users |
| 2 | Gemini CLI | CLI | ✅ Detailed | Google's official CLI |
| 3 | Zed | IDE | 🟡 Category | Growing IDE, Rust-based |
| 4 | Cline | Agent | ✅ Detailed | Autonomous coding agent |
| 5 | Cherry Studio | Chat | 🟡 Category | Popular chat UI |
| 6 | LibreChat | Chat | ✅ Detailed | Open source ChatGPT alternative |
| 7 | Continue | IDE | ✅ Detailed | VS Code + JetBrains |
| 8 | OpenCode | IDE | 🟡 Category | Alternative IDE |
| 9 | Roo Code | IDE | 🟡 Category | Specialized editor |
| 10 | Goose | Agent | 🟢 Community | Agent framework |
| 11 | MCP-Use | Bridge | ✅ Detailed | Free bridge solution |
| 12 | mcp-agent | Agent | 🟡 Category | Agent implementation |
| 13 | Inspector | Debug | 🟡 Category | MCP debugging tool |
| 14 | 5ire | Chat | ✅ Detailed | Beginner-friendly |
| 15 | fast-agent | Agent | 🟢 Community | Performance-focused |
| 16 | ChatMCP | Chat | 🟡 Category | Web-based chat |
| 17 | Open MCP Client | Generic | 🟡 Category | Reference implementation |
| 18 | Zola | CMS | 🟢 Community | Static site generator |
| 19 | MCPJam Inspector | Debug | 🟡 Category | Testing tool |
| 20 | HyperChat | Chat | 🟡 Category | Enhanced chat UI |
| 21 | FLUJO | Workflow | 🟢 Community | Workflow automation |
| 22 | Tome | Presentation | 🟢 Community | Presentation tool |
| 23 | CLI Inspector | Debug | 🟡 Category | CLI debugging |
| 24 | Groq Desktop | Desktop | 🟢 Community | Groq integration |
| 25 | Director | Orchestration | 🟢 Community | Multi-agent orchestration |
| 26 | Systemprompt | Prompt | 🟢 Community | Prompt management |
| 27 | Toolbase | Tools | 🟢 Community | Tool registry |
| 28 | Slack Assistant | Communication | 🟡 Category | Slack integration |
| 29 | ClaudeR | R Lang | 🟢 Community | R language integration |
| 30 | MCP Client Tester | Debug | 🟡 Category | Testing framework |

### Additional Clients (31-378+)

#### AI Development Tools (20+ clients)
| Client | Why Not Detailed | Testing Approach |
|--------|------------------|------------------|
| GenAIScript | Similar to other script tools | Category representative |
| Smolagents | Small agent framework | Community testing |
| TinyAgents | Lightweight variant | Community testing |
| Metis Router | Routing layer | Test with similar routers |
| AgentGraph | Visualization tool | Community testing |
| Y CLI | Another CLI variant | Category testing |
| Nerve | Neural framework | Specialized community |
| Minions | Multi-agent system | Agent category testing |
| Evo AI | Evolution-based | Research community |
| [... 11 more] | Various specializations | Community driven |

#### Communication/Chat UIs (35+ clients)
| Client | Why Not Detailed | Testing Approach |
|--------|------------------|------------------|
| Slack Assistant | Enterprise comms | Test with Slack users |
| Lark (Feishu) | Regional (China) | Regional community |
| Xiaohongshu | Social platform | Platform-specific |
| HyperChat | Enhanced features | Category testing |
| SeekChat | Search-focused | Feature testing |
| Scira MCP Chat | Alternative UI | Community |
| Hermes | Message routing | Category testing |
| UI-TARS Desktop | Desktop variant | Desktop category |
| Witsy | Personal assistant | Community |
| DeskAid | Desktop helper | Desktop category |
| [... 25 more] | UI variants | Category representatives |

#### Code Editors & IDEs (25+ clients)
| Client | Why Not Detailed | Testing Approach |
|--------|------------------|------------------|
| OpenCode | VS Code fork | Test as VS Code variant |
| Roo Code | Specialized editor | Category testing |
| MCPHub.nvim | Neovim plugin | Vim community |
| mcp.el | GNU Emacs | Emacs community |
| chat.md | Markdown-based | Document editors category |
| Amazon Q Developer CLI | AWS-specific | Enterprise testing |
| DeskAid (Git) | Git integration | VCS category |
| [... 18 more] | Editor variants | Category approach |

#### Terminal/CLI Tools (20+ clients)
| Client | Why Not Detailed | Testing Approach |
|--------|------------------|------------------|
| Oterm | Terminal variant | CLI category |
| Y CLI | Yet another CLI | Category testing |
| CLI | Generic CLI | Reference testing |
| Dive | Specialized CLI | Community |
| MCPM | Package manager | Infrastructure testing |
| CLI Client | Basic client | Category |
| Console Chat GPT | Console-based | Terminal category |
| [... 13 more] | CLI variants | Category representatives |

#### Framework Integrations (30+ clients)
| Client | Why Not Detailed | Testing Approach |
|--------|------------------|------------------|
| LangChain.js Adapters | Framework bridge | Test with LangChain users |
| Langgraph Tools | Graph framework | Graph tool category |
| Dify Plugin Agent | Plugin system | Plugin category |
| Vue Chat Interface | Vue.js specific | Frontend framework testing |
| Gradio UI Example | Gradio integration | ML UI category |
| Streamlit LLaMa | Streamlit app | Python app category |
| DrissionPage | Page automation | Automation category |
| [... 23 more] | Various frameworks | Framework-specific testing |

#### Mobile/Desktop Applications (15+ clients)
| Client | Why Not Detailed | Testing Approach |
|--------|------------------|------------------|
| Jan | Desktop app | Desktop category |
| UI-TARS Desktop | Desktop variant | Desktop testing |
| DeskAid | Helper app | Utility category |
| Witsy | Assistant app | Assistant category |
| Evo AI | AI app | AI apps category |
| Desktop Accessibility | Accessibility focus | Accessibility testing |
| [... 9 more] | App variants | Platform testing |

#### Specialized/Domain Tools (50+ clients)
| Client | Domain | Why Not Detailed | Testing Approach |
|--------|--------|------------------|------------------|
| GHOSTCREW | Cybersecurity | Specialized domain | Security community |
| Trading Agents | Finance | Domain-specific | Finance community |
| Recipe Manager | Cooking | Niche application | Hobby community |
| Home Assistant (Xiaozhi) | Smart Home | IoT specific | IoT community |
| QU3 | Quantum-Safe | Research tool | Academic community |
| Real Estate AI Agent | Real Estate | Industry-specific | Industry testing |
| RAG with AWS Bedrock | Enterprise | AWS-specific | AWS community |
| Protolint | Protocol testing | Dev tool | Developer testing |
| Markdown Processor | Documents | Document processing | Doc community |
| OmniConnect | Integration | Connector tool | Integration testing |
| Cobolt | Unknown | Unclear purpose | Community discovery |
| Saiki | Unknown | Unclear purpose | Community discovery |
| Ramparts | Security | Security tool | Security community |
| [... 37 more] | Various | Specialized uses | Domain experts |

#### Testing/Debug Tools (10+ clients)
| Client | Why Not Detailed | Testing Approach |
|--------|------------------|------------------|
| MCP Client Tester | Testing tool | Use for our testing |
| Inspector | Debug tool | Use for debugging |
| CLI Inspector | CLI debugging | CLI testing |
| MCPJam Inspector | Jam testing | Event testing |
| Protolint | Protocol lint | Protocol testing |
| [... 5 more] | Test variants | Testing infrastructure |

#### Regional/Language Specific (15+ clients)
| Client | Region/Language | Why Not Detailed | Testing Approach |
|--------|-----------------|------------------|------------------|
| Xiaohongshu | China | Regional platform | Chinese community |
| Lark (Feishu) | China | Regional tool | Chinese community |
| Xiaozhi AI | China | Regional variant | Chinese community |
| ClaudeR | R Language | Language-specific | R community |
| mcp.el | Emacs Lisp | Editor-specific | Emacs community |
| [... 10 more] | Various | Regional/language | Local communities |

#### Experimental/Research (20+ clients)
| Client | Focus | Why Not Detailed | Testing Approach |
|--------|-------|------------------|------------------|
| QU3 | Quantum | Research project | Academic testing |
| Evo AI | Evolution | Experimental | Research community |
| AgentGraph | Visualization | Research tool | Academic testing |
| fast-agent | Performance | Experimental | Performance testing |
| [... 16 more] | Various | Research/experimental | Academic partners |

#### Unknown/Unclear Purpose (30+ clients)
| Client | Status | Action Needed |
|--------|--------|---------------|
| Cobolt | Unknown | Need documentation |
| Saiki | Unknown | Community investigation |
| Tome | Unclear | Needs classification |
| Director | Unclear | Architecture review |
| Systemprompt | Unclear | Feature discovery |
| [... 25 more] | Unknown | Community discovery |

---

## Why We Don't Track Everything in Detail

### Resource Constraints
- Detailed testing takes time
- Many clients are variants of the same base
- Some clients have <100 users

### Practical Approach
- Test category representatives
- Let communities test their specialized tools
- Focus detailed effort on high-impact clients

### Open Source Philosophy
- We document everything's existence
- Community fills in the gaps
- Anyone can contribute testing data

---

## How to Help

### For Client Developers
1. Test DollhouseMCP with your client
2. Submit compatibility report
3. Suggest unique features/optimizations

### For DollhouseMCP Users
1. Report which clients you use
2. Share what works/doesn't work
3. Contribute testing for your favorite client

### For Communities
1. Adopt testing for your domain
2. Share domain-specific personas/skills
3. Document unique capabilities

---

## The Promise

**We commit to:**
- Never ignoring any MCP client
- Documenting all known clients
- Supporting community testing
- Celebrating the diversity of the ecosystem

**DollhouseMCP works everywhere MCP works** - all 378+ places and counting!

---

*This is a living document. As the MCP ecosystem grows, so does this list.*