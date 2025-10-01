# Generic Strategic Analysis Workspace Instructions for VS Code Agents

## Overview

This document provides comprehensive instructions for VS Code agents when working within strategic analysis workspaces. These guidelines ensure consistency, proper context awareness, and effective cross-referencing across all documentation for any industry, product, or market analysis project.

## Universal Workspace Structure and Context

### Primary Documentation Areas

1. **Competitive Intelligence** (`/competitive/`)
   - Competitor analysis and monitoring (`/competitive/[competitor-name]/`)
   - Market landscape overviews and positioning
   - Daily reports and historical competitive data
   - Automated monitoring configurations

2. **Customer Analysis** (`/customer-segmentation/`, `/customer-pain-points/`)
   - Detailed customer segmentation by relevant criteria
   - Revenue analysis and market sizing
   - Pain point documentation across segments and verticals
   - Customer journey mapping and persona development

3. **Strategic Initiatives** (`/initiatives/`)
   - Strategic roadmaps and implementation plans
   - Incubation projects and future opportunity assessments
   - Initiative-to-pain-point mapping and priority alignment

4. **Industry Vertical Analysis** (`/verticals/`)
   - Industry-specific pain points and priorities
   - Market segmentation and opportunity analysis
   - Regulatory and compliance requirements by vertical

5. **Research Documentation** (`/research/`)
   - Market research and trend analysis
   - Customer interview data and insights
   - Industry reports and external research synthesis

6. **Technical Documentation** (`/datasheets/`)
   - Product specifications and capabilities
   - Technical reference materials and architecture docs
   - Integration guides and implementation details

7. **Business Intelligence** (`/misc/`)
   - Presentation materials and executive summaries
   - Session templates and meeting frameworks
   - Reference documents and external resources

## Agent Guidelines for Document Creation

### 1. Context Awareness Requirements

**ALWAYS** review these key documents before writing new content:
- `README.md` - Project overview and current state
- `[PROJECT-NAME]-template.md` - Project-specific template and guidelines
- `customer-segmentation/segmentation-overview.md` - Customer context
- `customer-pain-points/README.md` - Pain point framework
- `competitive/competitive-landscape-overview.md` - Market positioning
- `initiatives/initiative-roadmap.md` - Strategic direction
- `verticals/README.md` - Industry context and priorities

### 2. Cross-Referencing Standards

**When writing documents, include relevant cross-references to:**

#### Customer Context
```markdown
- [Customer Segmentation Overview](../customer-segmentation/segmentation-overview.md)
- [Pain Point Priority Matrix](../customer-pain-points/pain-point-priority-matrix.md)
- [Customer Segment Analysis](../customer-segmentation/[segment-name]-analysis.md)
```

#### Competitive Intelligence
```markdown
- [Competitive Landscape Overview](../competitive/competitive-landscape-overview.md)
- [[Competitor] Analysis](../competitive/[competitor-name]/[competitor-name]-analysis.md)
- [Market Positioning Strategy](../competitive/competitive-positioning.md)
```

#### Strategic Initiatives
```markdown
- [Initiative Roadmap](../initiatives/initiative-roadmap.md)
- [[Initiative Name]](../initiatives/[initiative-name].md)
- [Pain Point Mapping](../initiatives/pain-point-mapping.md)
```

#### Industry Verticals
```markdown
- [Vertical Analysis Overview](../verticals/README.md)
- [[Vertical] Market Analysis](../verticals/[vertical-name].md)
- [Cross-Vertical Comparison](../verticals/vertical-comparison-matrix.md)
```

### 3. Industry-Agnostic Context Integration

**Always consider and reference relevant factors based on project domain:**

**For Technology Projects:**
- Security and compliance requirements
- Integration complexity and technical debt
- Scalability and performance requirements
- User experience and adoption challenges

**For Market Analysis Projects:**
- Regulatory environment and compliance
- Economic factors and market dynamics
- Customer behavior and preferences
- Competitive pressure and differentiation

**For Product Development Projects:**
- User needs and pain points
- Technical feasibility and constraints
- Market readiness and adoption barriers
- Competitive landscape and positioning

### 4. Universal Pain Point Categories

**Every strategic document should consider these common pain point categories:**
1. **Operational Complexity**
   - Reference: `customer-pain-points/operational-complexity.md`
2. **Cost and Resource Constraints**
   - Reference: `customer-pain-points/cost-resource-constraints.md`
3. **Integration and Compatibility Issues**
   - Reference: `customer-pain-points/integration-compatibility.md`
4. **Security and Compliance Challenges**
   - Reference: `customer-pain-points/security-compliance.md`
5. **Performance and Reliability Concerns**
   - Reference: `customer-pain-points/performance-reliability.md`
6. **Skills Gap and Training Needs**
   - Reference: `customer-pain-points/skills-gap-training.md`

### 5. Competitive Positioning Framework

**When discussing solutions, always consider:**
- Primary competitors' strengths and weaknesses
- Market gaps and white space opportunities
- Differentiation strategies and unique value propositions
- Competitive response strategies and defensive positioning
- Partnership opportunities and ecosystem dynamics

### 6. Document Structure Standards

#### Executive Documents
```markdown
# [Document Title]

## Executive Summary
Brief overview with key takeaways and strategic implications

## Strategic Context
Reference to customer pain points, market drivers, and business objectives

## Analysis Overview
Methodology, scope, and analytical approach

## Key Findings
Primary insights with supporting evidence and data

## Strategic Recommendations
Actionable recommendations with priorities and timelines

## Business Impact
Quantifiable benefits, ROI analysis, and success metrics

## Implementation Strategy
Phased approach with milestones and resource requirements

## Risk Assessment
Potential challenges and mitigation strategies

## Success Metrics
Measurable outcomes and KPIs

## Related Documentation
Cross-references to relevant workspace content

---
**Last Updated**: [Date]
**Next Review**: [Review Schedule]
**Owner**: [Responsible Team/Individual]
```

#### Analysis Documents
```markdown
# [Analysis Topic] Analysis

## Overview
Analysis summary, objectives, and scope

## Methodology
Research approach, data sources, and analytical methods

## Current State Assessment
Baseline analysis and key observations

## Gap Analysis
Identification of problems, opportunities, and unmet needs

## Options Analysis
Alternative approaches with pros, cons, and trade-offs

## Recommendations
Preferred approach with rationale and supporting evidence

## Implementation Considerations
Practical factors, constraints, and requirements

## Success Metrics
Measurement criteria and validation methods

## Related Documentation
Cross-references to supporting analysis

---
**Last Updated**: [Date]
**Analysis Period**: [Time Period Covered]
**Data Sources**: [Primary Sources Used]
```

#### Technical Documents
```markdown
# [Technical Document Title]

## Overview
Technical summary, purpose, and scope

## Architecture
System design, components, and relationships

## Requirements
Functional and non-functional requirements

## Use Cases
Customer scenarios and application examples

## Implementation Details
Technical specifications, configurations, and procedures

## Integration Points
Connections to existing systems and processes

## Testing and Validation
Verification methods and acceptance criteria

## Deployment Considerations
Implementation planning and operational requirements

## Related Documentation
Technical cross-references and dependencies

---
**Last Updated**: [Date]
**Version**: [Document Version]
**Technical Owner**: [Responsible Team]
```

### 7. Terminology and Consistency Guidelines

**Maintain consistent terminology throughout the workspace:**
- Use project-specific terminology as defined in the main template
- Maintain consistent naming conventions for files and folders
- Use standard industry terminology where applicable
- Define acronyms and technical terms in a glossary when needed

**Common Business Terms:**
- **Total Addressable Market (TAM)** - Total market demand
- **Serviceable Addressable Market (SAM)** - Realistically addressable portion
- **Return on Investment (ROI)** - Financial benefit measurement
- **Key Performance Indicators (KPIs)** - Success measurement metrics
- **Minimum Viable Product (MVP)** - Basic functional version

### 8. Data and Evidence Requirements

**Support all claims and recommendations with:**
- Customer research data from `/customer-segmentation/` and `/customer-pain-points/`
- Market intelligence from `/competitive/` and `/research/`
- Industry insights from `/verticals/`
- Technical validation from `/datasheets/` and implementation guides
- Financial analysis and ROI calculations where applicable

### 9. Version Control and Collaboration Standards

**When updating documents:**
1. Review git history for context on previous changes
2. Maintain consistency with existing document structure and style
3. Update cross-references when moving or renaming files
4. Use descriptive commit messages referencing the business context
5. Tag major document versions for easy reference
6. Maintain change logs for significant updates

### 10. Quality Assurance Framework

**Before finalizing any document, verify:**

- [ ] Document addresses relevant stakeholder needs
- [ ] Appropriate context from related workspace documentation
- [ ] Consistent terminology and formatting throughout
- [ ] Cross-references are accurate and up-to-date
- [ ] Supporting data and evidence is current and relevant
- [ ] Recommendations are actionable and specific
- [ ] Success metrics are defined and measurable
- [ ] Implementation approach is realistic and feasible
- [ ] Risk factors are identified and addressed
- [ ] Related documentation section is complete

## Content Quality Standards

### Research and Analysis Quality
- Use multiple sources to validate findings
- Clearly distinguish between facts, assumptions, and opinions
- Provide confidence levels for predictions and estimates
- Document limitations and potential biases in analysis
- Regular updates to maintain currency and relevance

### Writing and Presentation Quality
- Use clear, concise language appropriate for the target audience
- Structure documents logically with clear section hierarchy
- Include executive summaries for longer documents
- Use visual aids (charts, diagrams) where helpful
- Maintain professional tone while being accessible

### Data and Evidence Quality
- Cite sources and provide links where possible
- Use recent data and validate currency
- Distinguish between quantitative and qualitative evidence
- Provide context for statistical information
- Document data collection and analysis methods

## Agent-Specific Instructions

### When Analyzing Competitive Intelligence
1. Always cross-reference with existing analyses in `/competitive/`
2. Consider impact on customer segments from `/customer-segmentation/`
3. Identify opportunities to address pain points in `/customer-pain-points/`
4. Reference industry-specific implications from `/verticals/`
5. Update competitive positioning based on new intelligence

### When Developing Strategic Initiatives
1. Start with customer pain point analysis and validation
2. Review competitive positioning and market dynamics
3. Consider implementation across multiple customer segments
4. Define clear success metrics and business impact measurement
5. Identify cross-initiative dependencies and synergies
6. Develop realistic timelines and resource requirements

### When Writing Market Analysis
1. Reference existing market data in `/research/` and `/customer-segmentation/`
2. Consider regulatory and industry-specific factors from `/verticals/`
3. Include competitive context and positioning implications
4. Address market sizing and opportunity quantification
5. Identify key trends and driving factors
6. Provide actionable insights for strategic planning

### When Creating Technical Documentation
1. Reference existing specifications in `/datasheets/`
2. Consider integration requirements with current solutions
3. Address security, compliance, and regulatory requirements
4. Include use cases from different customer segments and verticals
5. Define testing, validation, and acceptance criteria
6. Document deployment and operational considerations

## Workspace Maintenance Guidelines

### Regular Maintenance Tasks
- **Weekly**: Update competitive intelligence and market data
- **Monthly**: Review and update cross-references across documents
- **Quarterly**: Validate document accuracy and relevance
- **Semi-annually**: Comprehensive workspace structure review
- **Annually**: Archive outdated content and reorganize as needed

### File and Folder Management
- Use consistent naming conventions throughout
- Organize files logically within appropriate folders
- Archive outdated documents to `/archive/` or `/history/` folders
- Maintain clean folder structures without orphaned files
- Regular cleanup of temporary and draft files

### Git Repository Best Practices
- Use descriptive commit messages with business context
- Create branches for major document updates or restructuring
- Tag important milestones and document versions
- Regular pushes to preserve work and enable collaboration
- Maintain clean commit history with meaningful messages

## Automation and Integration

### MCP Server Integration
**When using MCP servers for data collection and analysis:**
- Configure monitoring for competitive intelligence gathering
- Set up automated data collection for market research
- Use consistent data formats and structures
- Store configuration files in appropriate directories
- Follow monitoring guidelines for regular updates

### Analysis Automation
- Use analysis scripts in `/[analysis-area]/analysis-scripts/`
- Maintain data processing pipelines for regular updates
- Automate report generation where appropriate
- Set up alerts for significant market or competitive changes
- Document automation procedures and maintenance requirements

## Example Document References

Reference these examples for proper structure and context integration:
- Main project README for overall structure and navigation
- Competitive landscape overview for market positioning
- Customer segmentation analysis for target market definition
- Pain point analysis for problem identification and validation
- Strategic initiative documents for implementation planning

## Customization Guidelines

This instruction framework can be adapted for specific projects by:

1. **Adding domain-specific folders and documentation types**
2. **Modifying pain point categories for industry relevance**
3. **Adapting competitive analysis frameworks for market specifics**
4. **Customizing document templates for project requirements**
5. **Scaling structure complexity based on project size and duration**

## Success Metrics for Workspace Quality

### Documentation Quality Metrics
- Consistency in terminology and formatting across documents
- Accuracy and currency of cross-references
- Completeness of analysis coverage across key areas
- Regular updates and maintenance of content

### Collaboration Effectiveness
- Team adoption of workspace standards and procedures
- Efficiency in finding and using relevant documentation
- Quality of cross-team communication and knowledge sharing
- Reduction in duplicated work and analysis

### Strategic Impact
- Actionability of recommendations and insights
- Integration of analysis into decision-making processes
- Measurable business impact from strategic initiatives
- Stakeholder satisfaction with documentation quality and utility

---

This instruction framework ensures that all VS Code agents working in strategic analysis workspaces maintain consistency, proper context awareness, and effective cross-referencing across comprehensive project documentation, regardless of industry or domain focus.

**Document Version**: 1.0  
**Last Updated**: September 30, 2025  
**Next Review**: Quarterly  
**Applicable To**: All strategic analysis workspace projects
