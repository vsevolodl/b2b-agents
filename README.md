# B2B Commercial Agents Repository

This repository contains a comprehensive collection of specialized AI agent definitions for Claude Code's sub-agent system, specifically designed for B2B commercial operations. The agents accelerate sales, marketing, and business operations using strategic frameworks and proven methodologies.

## Repository Overview

This repository provides **40 specialized commercial agents** across **8 categories** (83% complete), optimized for B2B enterprise sales cycles, account-based marketing, and long-term customer relationships. Each agent follows proven commercial frameworks and integrates with rapid iteration methodologies.

## 📥 Installation

1. **Download this repository:**
   ```bash
   git clone [repository-url]
   ```

2. **Copy to your Claude Code agents directory:**
   ```bash
   cp -r b2b-commercial-agents/* ~/.claude/agents/
   ```
   
   Or manually copy all the agent files to your `~/.claude/agents/` directory.

3. **Restart Claude Code** to load the new agents.

## 🚀 Quick Start

Agents are automatically available in Claude Code. Simply describe your commercial task and the appropriate agent will be triggered. You can also explicitly request an agent by mentioning their name.

📚 **Learn more:** [Claude Code Sub-Agents Documentation](https://docs.anthropic.com/en/docs/claude-code/sub-agents)

### Example Usage
- "Analyze our main competitor's positioning strategy" → `market-intelligence-analyst`
- "Create value propositions for our enterprise customers" → `value-proposition-architect`
- "We need to expand revenue in our existing accounts" → `expansion-revenue-manager`
- "Develop a LinkedIn outreach strategy for enterprise prospects" → `linkedin-social-seller`

## 📁 Directory Structure

Agents are organized by commercial function for easy discovery:

```
b2b-agents/
├── market-strategy/                    # 6 agents ✅
│   ├── competitive-monitor.md
│   ├── customer-insight-researcher.md
│   ├── market-intelligence-analyst.md
│   ├── product-strategist.md
│   ├── requirements-coordinator.md
│   └── value-proposition-architect.md
├── content-messaging/                  # 5 agents ✅
│   ├── content-engine.md
│   ├── messaging-strategist.md
│   ├── pr-communications.md
│   ├── sales-enablement-creator.md
│   └── webinar-content-specialist.md
├── demand-generation/                  # 6 agents ✅
│   ├── account-based-marketer.md
│   ├── campaign-orchestrator.md
│   ├── intent-data-specialist.md
│   ├── lead-generation-engine.md
│   ├── linkedin-social-seller.md
│   └── webinar-lead-converter.md
├── sales-execution/                    # 8 agents ✅
│   ├── account-executive.md
│   ├── enterprise-sales-manager.md
│   ├── objection-response-handler.md
│   ├── proposal-deal-coordinator.md
│   ├── sales-development-specialist.md
│   ├── sales-engineer.md
│   ├── sales-process-optimizer.md
│   └── sales-trainer-enabler.md
├── customer-lifecycle/                 # 7 agents ✅
│   ├── customer-experience-designer.md
│   ├── customer-success-orchestrator.md
│   ├── expansion-revenue-manager.md
│   ├── feedback-community-manager.md
│   ├── product-adoption-specialist.md
│   ├── retention-specialist.md
│   └── support-knowledge-coordinator.md
├── revenue-operations/                 # 6 agents ✅
│   ├── crm-operations-manager.md
│   ├── performance-metrics-designer.md
│   ├── pricing-package-strategist.md
│   ├── revenue-analyst.md
│   ├── revenue-recognition-specialist.md
│   └── territory-quota-planner.md
├── partnerships/                       # 2/5 agents 🔄
│   ├── channel-program-manager.md
│   ├── partnership-strategist.md
│   ├── [integration-marketplace-coordinator.md] 📋
│   ├── [influencer-analyst-relations.md] 📋
│   └── [vendor-procurement-specialist.md] 📋
└── business-operations/                # 0/5 agents 📋
    ├── [business-intelligence-coordinator.md] 📋
    ├── [compliance-security-manager.md] 📋
    ├── [financial-planning-analyst.md] 📋
    ├── [legal-contract-specialist.md] 📋
    └── [operations-automation-coordinator.md] 📋
```

**Legend:**
- ✅ Complete category (all agents implemented)
- 🔄 Partial category (some agents missing)  
- 📋 Missing agents (planned for future implementation)

## Agent Architecture

Each agent is defined in a Markdown file with YAML frontmatter containing:
- `name`: Unique kebab-case identifier for the agent
- `description`: Comprehensive usage scenarios with 4 detailed examples including context and commentary
- `color`: Visual identification color for the agent category
- `tools`: Available Claude Code tools (Write, Read, MultiEdit, WebSearch, Task, etc.)

The system prompt follows with 500+ words defining:
- Agent identity and specialized expertise
- 6 primary responsibilities with detailed implementation guidance
- Domain-specific frameworks, methodologies, and best practices
- Integration with rapid iteration and sprint methodologies
- Cross-functional collaboration patterns
- Success metrics and performance measurement approaches

## Commercial Philosophy

This agent system is built around **B2B commercial excellence** and **enterprise sales optimization**:

### Core Principles:
- **Customer-centric value creation** over feature-focused selling
- **Long-term relationship building** over transactional interactions
- **Data-driven decision making** over intuition-based strategies
- **Cross-functional alignment** over siloed operations
- **Continuous optimization** over set-and-forget approaches
- **Strategic thinking** over tactical execution alone

### B2B Specialization:
- **Complex sales cycles** with multiple stakeholders and decision makers
- **Account-based approaches** for enterprise customer acquisition and expansion
- **Value-based selling** with quantified ROI and business case development
- **Strategic partnerships** for ecosystem development and market expansion
- **Compliance and security** requirements for enterprise customers
- **Long-term customer success** and expansion revenue optimization

## Working with Agents

### Installation
Agents are deployed by copying to `~/.claude/agents/` directory. No build process is required as they are pure Markdown configuration files.

### Agent Categories & Use Cases

#### **Market Strategy Agents**
Use for market analysis, competitive intelligence, product strategy, and strategic planning:
- Market opportunity assessment and competitive positioning
- Product roadmap planning and go-to-market strategy
- Value proposition development and customer insight analysis
- ICP refinement and market segmentation

#### **Content & Messaging Agents**  
Use for brand building, messaging strategy, and content development:
- Brand positioning and messaging architecture
- Content strategy and thought leadership development
- Sales enablement materials and competitive positioning
- PR strategy and webinar content creation

#### **Demand Generation Agents**
Use for lead generation, marketing campaigns, and pipeline development:
- Multi-channel campaign orchestration and optimization
- LinkedIn and social selling strategies
- Account-based marketing for enterprise targets
- Intent data analysis and lead qualification

#### **Sales Execution Agents**
Use for direct sales activities, deal management, and sales optimization:
- Sales development and lead qualification
- Enterprise sales and complex deal management
- Sales engineering and technical demonstrations
- Proposal development and deal closing

#### **Customer Lifecycle Agents**
Use for customer success, expansion, and retention optimization:
- Customer onboarding and success orchestration
- Expansion revenue and account growth strategies
- Customer experience design and feedback management
- Product adoption and retention optimization

#### **Revenue Operations Agents**
Use for sales analytics, pricing strategy, and operational optimization:
- Revenue forecasting and pipeline analysis
- Pricing strategy and package optimization
- CRM operations and performance measurement
- Territory planning and quota management

#### **Partnership Agents**
Use for strategic alliances, channel development, and ecosystem growth:
- Partnership strategy and channel program management
- Integration partnerships and marketplace optimization
- Influencer and analyst relations
- Vendor management and procurement

#### **Business Operations Agents**
Use for legal, financial, and operational support:
- Financial planning and business intelligence
- Legal compliance and contract management
- Operations automation and process optimization
- Security compliance and risk management

### Common Agent Workflows

#### **New Market Entry**
`market-intelligence-analyst` → `product-strategist` → `value-proposition-architect` → `messaging-strategist` → `campaign-orchestrator` → `sales-development-specialist`

#### **Enterprise Sales Process**
`account-based-marketer` → `linkedin-social-seller` → `sales-development-specialist` → `enterprise-sales-manager` → `proposal-deal-coordinator` → `customer-success-orchestrator`

#### **Customer Expansion**
`customer-success-orchestrator` → `expansion-revenue-manager` → `product-adoption-specialist` → `feedback-community-manager` → `retention-specialist`

#### **Competitive Response**
`competitive-monitor` → `value-proposition-architect` → `objection-response-handler` → `sales-enablement-creator` → `messaging-strategist`

#### **Product Launch**
`product-strategist` → `messaging-strategist` → `content-engine` → `webinar-content-specialist` → `campaign-orchestrator` → `sales-trainer-enabler`

## Integration Patterns

### Cross-Functional Coordination
- **Marketing ↔ Sales**: Messaging alignment, lead qualification, and feedback loops
- **Sales ↔ Customer Success**: Handoff optimization, expansion opportunities, and customer insights
- **Product ↔ Marketing**: Roadmap alignment, positioning strategy, and launch coordination
- **Operations ↔ All Functions**: Process optimization, analytics, and performance measurement

### Sprint Methodology Adaptation
**6-Day Commercial Sprints**:
- **Day 1**: Research, analysis, and strategic planning
- **Day 2**: Strategy development and cross-functional alignment
- **Day 3-4**: Execution, campaign launch, or deal progression
- **Day 5**: Performance measurement and optimization
- **Day 6**: Iteration planning and process improvement

**Cycle Coordination**:
- **Strategic Agents**: 4-6 week planning cycles for market analysis and positioning
- **Campaign Agents**: 2-3 week execution cycles for marketing and demand generation  
- **Sales Agents**: 1-2 week progression cycles for deal advancement and closing
- **Operations Agents**: Continuous optimization cycles for process and performance improvement

## Key Differentiators

### B2B Commercial Optimization
- **Enterprise focus** with complex stakeholder management and long sales cycles
- **Account-based strategies** for high-value customer acquisition and expansion
- **Value-based selling** with quantified business cases and ROI demonstration
- **Strategic partnerships** for ecosystem development and competitive advantage
- **Compliance readiness** for enterprise security and regulatory requirements

### Integrated Commercial Operations
- **End-to-end coverage** from market research through customer expansion
- **Cross-functional alignment** between marketing, sales, and customer success
- **Data-driven optimization** with comprehensive analytics and performance measurement
- **Scalable processes** that grow with business expansion and team development
- **Continuous improvement** through feedback loops and performance optimization

### Modern Commercial Methodologies
- **Account-Based Marketing (ABM)** for enterprise customer targeting
- **Value-Based Selling** with business case development and ROI quantification
- **Customer Success Management** for expansion revenue and retention optimization
- **Revenue Operations** for data-driven sales and marketing alignment
- **Strategic Partnership Development** for ecosystem growth and competitive advantage

## Getting Started

### For Sales Teams
1. Start with `sales-development-specialist` for lead qualification and pipeline development
2. Use `account-executive` for deal progression and customer relationship management
3. Leverage `enterprise-sales-manager` for complex, multi-stakeholder sales processes
4. Apply `proposal-deal-coordinator` for deal structuring and closing

### For Marketing Teams  
1. Begin with `market-intelligence-analyst` for market research and competitive analysis
2. Use `messaging-strategist` for brand positioning and value proposition development
3. Leverage `campaign-orchestrator` for multi-channel marketing campaign management
4. Apply `account-based-marketer` for enterprise customer targeting and engagement

### For Customer Success Teams
1. Start with `customer-success-orchestrator` for onboarding and relationship management
2. Use `expansion-revenue-manager` for account growth and upsell opportunities
3. Leverage `product-adoption-specialist` for usage optimization and feature adoption
4. Apply `retention-specialist` for churn prevention and customer satisfaction

### For Operations Teams
1. Begin with `revenue-analyst` for sales performance and pipeline analysis
2. Use `crm-operations-manager` for system optimization and process improvement
3. Leverage `performance-metrics-designer` for KPI development and measurement
4. Apply `business-intelligence-coordinator` for cross-functional analytics and insights

## Agent Performance Measurement

### Success Metrics by Category
- **Market Strategy**: Market share growth, competitive win rates, product-market fit scores
- **Content & Messaging**: Message resonance, content engagement, sales enablement effectiveness
- **Demand Generation**: Lead quality scores, pipeline velocity, campaign ROI
- **Sales Execution**: Win rates, deal size, sales cycle length, quota attainment
- **Customer Lifecycle**: Customer satisfaction, expansion revenue, retention rates
- **Revenue Operations**: Forecast accuracy, process efficiency, performance optimization
- **Partnerships**: Partner revenue, channel effectiveness, ecosystem growth
- **Business Operations**: Process automation, compliance scores, operational efficiency

### Optimization Approach
- **Data-driven iteration** based on performance metrics and customer feedback
- **Cross-functional coordination** for process improvement and alignment optimization
- **Customer-centric refinement** based on satisfaction scores and success outcomes
- **Competitive adaptation** based on market changes and competitive dynamics
- **Technology integration** for automation and efficiency improvement

## No Build Commands

This repository contains only documentation files (Markdown). There are no build, test, or deployment commands as this is a configuration repository for Claude Code agents. Changes are applied by copying files to the Claude Code agents directory and restarting Claude Code.

## Customization Guidelines

When modifying agents for your specific business:

### Content Customization
1. **Industry Specialization**: Adapt examples and frameworks for your specific industry vertical
2. **Company Size Focus**: Customize for your target market (SMB, Mid-Market, Enterprise)
3. **Geographic Markets**: Adapt for regional differences in business practices and regulations
4. **Product Categories**: Align examples with your specific product or service offerings

### Process Integration
1. **CRM Integration**: Adapt workflows for your specific CRM system and data structure
2. **Sales Methodology**: Align with your company's sales process (MEDDIC, Challenger, Solution Selling)
3. **Marketing Stack**: Integrate with your marketing automation and campaign management tools
4. **Customer Success Platform**: Align with your customer success management and expansion processes

### Performance Optimization
1. **Metric Alignment**: Customize success metrics to match your business objectives and KPIs
2. **Workflow Optimization**: Adapt agent interactions for your specific business processes
3. **Stakeholder Mapping**: Customize for your organization's structure and decision-making processes
4. **Competitive Landscape**: Adapt competitive positioning for your specific market dynamics

### Testing and Validation
1. **Pilot Programs**: Test agents with specific use cases before full deployment
2. **Performance Measurement**: Establish baseline metrics and improvement targets
3. **User Feedback**: Collect feedback from sales, marketing, and customer success teams
4. **Iteration Cycles**: Plan regular agent updates based on performance and market changes

This repository provides the foundation for world-class B2B commercial operations, combining proven methodologies with modern AI assistance to accelerate revenue growth and customer success.