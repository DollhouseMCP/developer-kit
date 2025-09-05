# RAPPEL Framework Implementation for DollhouseMCP

## Overview

The RAPPEL Framework, created by Christopher S. Penn of Trust Insights, provides a structured approach for optimizing AI conversations. This guide shows how to implement RAPPEL using DollhouseMCP's persona and skill system.

**RAPPEL** stands for:
- **R**ole - Define the AI's role and expertise
- **A**ction - Specify the overall action plan
- **P**rime - Load relevant background knowledge
- **P**rompt - Provide the specific task or question
- **E**xecute - Run the task with the primed context
- **L**earn - Iterate and improve based on results

Original framework: https://trustinsights.ai/rappel

---

## DollhouseMCP Implementation Strategy

### 1. ROLE - Using Personas

DollhouseMCP personas perfectly implement the Role component:

```yaml
# Example: Data Analyst Persona
name: data-analyst-rappel
description: Expert data analyst specializing in statistical analysis and insights
content: |
  # Data Analyst Role (RAPPEL Framework)
  
  You are a senior data analyst with 15 years of experience in:
  - Statistical modeling and analysis
  - Business intelligence and reporting
  - Predictive analytics and forecasting
  - Data visualization and storytelling
  
  Your approach emphasizes accuracy, clarity, and actionable insights.
```

**Best Practices for Role Definition:**
- Be specific about expertise areas
- Include years of experience or level of expertise
- Define communication style and approach
- Specify any methodologies or frameworks they use

### 2. ACTION - Using Skills

Skills define the action plan and methodology:

```yaml
# Example: Market Analysis Action Skill
name: market-analysis-action
description: Structured approach for comprehensive market analysis
content: |
  # Market Analysis Action Plan
  
  When conducting market analysis, follow this systematic approach:
  
  1. **Data Collection Phase**
     - Gather market size and growth data
     - Identify key competitors
     - Analyze customer segments
  
  2. **Analysis Phase**
     - Perform SWOT analysis
     - Calculate market share
     - Identify trends and patterns
  
  3. **Synthesis Phase**
     - Generate insights and recommendations
     - Create visual representations
     - Prepare executive summary
```

### 3. PRIME - Using Context Templates

Templates provide the priming information:

```yaml
# Example: Company Context Template
name: company-context-prime
description: Background information for analysis tasks
content: |
  # Company Context (Priming Information)
  
  ## Business Overview
  Company: {{company_name}}
  Industry: {{industry}}
  Founded: {{founded_year}}
  Revenue: {{annual_revenue}}
  Employees: {{employee_count}}
  
  ## Products/Services
  {{products_services}}
  
  ## Target Market
  {{target_market}}
  
  ## Competitive Landscape
  {{competitors}}
  
  ## Current Challenges
  {{challenges}}
```

### 4. PROMPT - Task Specification

The prompt is the specific request, enhanced by the primed context:

```yaml
# Example: Analysis Prompt Template
name: analysis-prompt-template
description: Structured prompt for analysis tasks
content: |
  Given the context provided, please {{analysis_type}}:
  
  Specific Focus Areas:
  - {{focus_area_1}}
  - {{focus_area_2}}
  - {{focus_area_3}}
  
  Deliverables Required:
  - {{deliverable_1}}
  - {{deliverable_2}}
  
  Constraints:
  - {{constraints}}
```

### 5. EXECUTE - Using Agents

Agents orchestrate the complete RAPPEL execution:

```yaml
# Example: RAPPEL Market Analysis Agent
name: rappel-market-analysis
description: Complete RAPPEL implementation for market analysis
personas:
  - data-analyst-rappel           # ROLE
skills:
  - market-analysis-action         # ACTION
templates:
  - company-context-prime          # PRIME
  - analysis-prompt-template       # PROMPT structure

instructions: |
  ## RAPPEL Execution Flow
  
  1. **Activate Role**: Load data analyst persona
  2. **Set Action Plan**: Apply market analysis methodology
  3. **Prime Context**: Populate company and market information
  4. **Process Prompt**: Execute specific analysis request
  5. **Execute Analysis**: Generate comprehensive results
  6. **Learn & Iterate**: Document insights for improvement
```

### 6. LEARN - Using Memory Elements

Memory elements capture learnings for continuous improvement:

```yaml
# Example: Analysis Patterns Memory
name: market-analysis-patterns
description: Learned patterns and improvements from analyses
content: |
  # Market Analysis Learning Log
  
  ## Successful Patterns
  - Visual dashboards increase stakeholder engagement by 40%
  - Starting with competitive landscape provides better context
  - Including 3-year trends improves prediction accuracy
  
  ## Common Pitfalls
  - Overloading with technical jargon reduces clarity
  - Missing regional variations leads to incomplete analysis
  - Ignoring indirect competitors misses market threats
  
  ## Refinements
  - Always include executive summary upfront
  - Use industry-standard metrics for comparability
  - Provide confidence intervals for predictions
```

---

## Complete RAPPEL Implementation Example

### Step 1: Create the Ensemble

```bash
# Create a RAPPEL ensemble for comprehensive analysis
dollhouse create ensemble rappel-complete-analysis
```

### Step 2: Configure Components

```yaml
name: rappel-complete-analysis
description: Full RAPPEL framework implementation
components:
  personas:
    - business-strategist-role
    - data-analyst-role
    - market-researcher-role
  
  skills:
    - structured-analysis-action
    - data-collection-action
    - insight-generation-action
  
  templates:
    - company-context-prime
    - market-data-prime
    - competitive-landscape-prime
  
  agents:
    - rappel-orchestrator
  
  memory:
    - analysis-patterns
    - successful-approaches
    - client-preferences
```

### Step 3: Activation Sequence

```bash
# Activate the complete RAPPEL framework
dollhouse activate ensemble rappel-complete-analysis

# The system now has:
# - ROLE: Multiple expert personas activated
# - ACTION: Structured methodology loaded
# - PRIME: Context templates ready
# - PROMPT: Awaiting specific request
# - EXECUTE: Ready to process
# - LEARN: Memory system active
```

---

## Usage Patterns

### Pattern 1: Quick Analysis

```markdown
1. Activate: `rappel-quick-analyst` persona (combines R+A)
2. Prime: Load minimal context via template
3. Prompt: Direct question
4. Execute: Get rapid insights
```

### Pattern 2: Deep Research

```markdown
1. Role: Activate multiple specialist personas
2. Action: Load comprehensive methodology skills
3. Prime: Extensive context from multiple templates
4. Prompt: Complex multi-part question
5. Execute: Detailed analysis with cross-validation
6. Learn: Update memory with new patterns
```

### Pattern 3: Iterative Refinement

```markdown
1. Start with basic RAPPEL setup
2. Execute initial analysis
3. Learn from results
4. Adjust Role/Action/Prime based on feedback
5. Re-execute with refined approach
6. Document improvements in memory
```

---

## Best Practices

### 1. Role Selection
- Match role expertise to task requirements
- Consider combining complementary roles
- Update roles based on learned preferences

### 2. Action Planning
- Break complex actions into clear steps
- Include decision points and alternatives
- Document time estimates for each phase

### 3. Priming Strategy
- Load only relevant context to avoid overload
- Structure priming data for easy scanning
- Update prime templates with current information

### 4. Prompt Engineering
- Be specific about desired outputs
- Include success criteria
- Specify any constraints or requirements

### 5. Execution Optimization
- Monitor token usage during execution
- Cache frequently used combinations
- Parallelize independent components

### 6. Learning Integration
- Review outputs for quality patterns
- Update components based on successes
- Share learnings across similar use cases

---

## DollhouseMCP Advantages for RAPPEL

1. **Persistent Roles**: Personas maintain role consistency across sessions
2. **Reusable Actions**: Skills can be mixed and matched for different contexts
3. **Template Priming**: Structured templates ensure complete context loading
4. **Agent Orchestration**: Complex RAPPEL flows automated via agents
5. **Learning Memory**: Continuous improvement through memory elements
6. **Version Control**: Track evolution of RAPPEL components over time

---

## Quick Start Commands

```bash
# Install RAPPEL framework components
dollhouse install collection/frameworks/rappel-starter-pack

# Activate basic RAPPEL setup
dollhouse activate persona business-analyst-rappel
dollhouse activate skill structured-analysis-action
dollhouse activate template context-primer

# Execute with specific prompt
"Analyze the market opportunity for [your product] using the RAPPEL framework"
```

---

## Additional Resources

- Original RAPPEL Framework: https://trustinsights.ai/rappel
- Christopher Penn's Blog: https://www.christopherspenn.com/
- Trust Insights: https://trustinsights.ai/

---

*This implementation guide shows how DollhouseMCP's modular architecture perfectly aligns with the RAPPEL framework, enabling systematic, reproducible AI conversations with continuous learning.*