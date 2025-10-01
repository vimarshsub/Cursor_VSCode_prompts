# Strategic Analysis Project Structure Template

## Overview

This template provides a standardized directory structure and file organization system for comprehensive strategic analysis projects. It's designed to facilitate systematic research, analysis, and documentation across any topic or industry.

## Directory Structure Template

```
[PROJECT-NAME]/
├── README.md
├── project-workspace.code-workspace
├── [TOPIC]-template.md
├── competitive/
│   ├── README.md
│   ├── [competitor-1]/
│   │   ├── [competitor-1]-analysis.md
│   │   ├── [competitor-1]-strengths-weaknesses.md
│   │   ├── [competitor-1]-market-position.md
│   │   └── [competitor-1]-strategic-response.md
│   ├── [competitor-2]/
│   └── competitive-landscape-overview.md
├── customer-pain-points/
│   ├── README.md
│   ├── [pain-point-1].md
│   ├── [pain-point-2].md
│   ├── [pain-point-3].md
│   ├── pain-point-priority-matrix.md
│   └── cross-segment-analysis.md
├── customer-segmentation/
│   ├── README.md
│   ├── segmentation-overview.md
│   ├── [segment-1]-analysis.md
│   ├── [segment-2]-analysis.md
│   ├── segment-comparison.md
│   ├── data/
│   │   ├── raw-data.csv
│   │   └── processed-data.csv
│   └── analysis-scripts/
│       └── segment_analyzer.py
├── datasheets/
│   ├── [product-1]-datasheet.pdf
│   ├── [product-2]-datasheet.pdf
│   └── technical-specifications/
├── initiatives/
│   ├── [initiative-1].md
│   ├── [initiative-2].md
│   ├── initiative-roadmap.md
│   ├── pain-point-mapping.md
│   └── incubation/
│       ├── [experimental-initiative-1].md
│       └── research-projects/
├── misc/
│   ├── session-templates/
│   ├── presentation-materials/
│   └── reference-documents/
├── personas/
│   ├── README.md
│   ├── [persona-1].md
│   ├── [persona-2].md
│   ├── persona-comparison.md
│   └── journey-mapping/
├── research/
│   ├── README.md
│   ├── [research-topic-1].md
│   ├── [research-topic-2].md
│   ├── market-analysis.md
│   ├── trend-analysis.md
│   └── incubation/
│       ├── emerging-technologies.md
│       └── future-scenarios.md
└── verticals/
    ├── README.md
    ├── [vertical-1].md
    ├── [vertical-2].md
    ├── [vertical-3].md
    ├── vertical-comparison-matrix.md
    ├── pain-point-priority-matrix.md
    └── research-data/
        ├── [vertical-1]-research.md
        └── industry-reports/
```

## File Templates and Naming Conventions

### 1. README Files Structure

**Main README.md:**
```markdown
# [PROJECT NAME]

## Overview
[Brief description of the project and its objectives]

## Directory Structure
[Overview of the organization and what each folder contains]

## Key Findings
[Summary of major insights and conclusions]

## Getting Started
[Instructions for navigating and using the project]

## Data Sources
[List of data sources and references used]

## Last Updated
[Date and version information]
```

**Folder-level README.md:**
```markdown
# [FOLDER NAME]

## Purpose
[What this folder contains and why]

## Contents
[List of key files and their purposes]

## Key Insights
[Summary of main findings in this area]

## Related Folders
[Cross-references to related analysis]
```

### 2. Analysis File Templates

**Customer Segment Analysis Template:**
```markdown
# [SEGMENT NAME] Analysis

## Executive Summary
[Key findings and strategic implications]

## Segment Overview
- **Size**: [Number of customers/revenue]
- **Characteristics**: [Defining attributes]
- **Strategic Priority**: [High/Medium/Low]

## Detailed Analysis
### Demographics
[Segment composition and characteristics]

### Pain Points
[Primary challenges and needs]

### Opportunities
[Strategic opportunities and potential]

### Competitive Position
[How competitors are positioned]

## Strategic Recommendations
[Actionable recommendations]

## Data Sources
[References and sources used]
```

**Competitive Analysis Template:**
```markdown
# [COMPETITOR NAME] Competitive Analysis

## Executive Summary
[Key competitive threats and opportunities]

## Company Overview
- **Market Position**: [Leader/Challenger/Follower]
- **Revenue**: [If available]
- **Key Strengths**: [Top 3-4 strengths]
- **Key Weaknesses**: [Top 3-4 weaknesses]

## Product/Service Analysis
[Detailed comparison of offerings]

## Market Strategy
[Go-to-market approach and positioning]

## Customer Segments
[Target segments and approach]

## Competitive Response Strategy
[How to compete effectively]

## Threat Assessment
[Risk level and monitoring requirements]
```

**Pain Point Analysis Template:**
```markdown
# [PAIN POINT NAME]

## Problem Statement
[Clear definition of the customer problem]

## Current Impact
[Quantified business impact where possible]

## Root Causes
[Underlying causes and contributing factors]

## Customer Segments Affected
[Which segments experience this pain point]

## Competitive Context
[How competitors address this pain point]

## Solution Requirements
[What's needed to address the problem]

## Business Case
[ROI and value proposition for solving]

## Implementation Considerations
[Challenges and requirements for solutions]
```

### 3. Naming Conventions

**Files:**
- Use lowercase with hyphens: `customer-segment-analysis.md`
- Include topic prefix: `[topic]-[specific-area].md`
- Use descriptive names: `pain-point-priority-matrix.md`

**Folders:**
- Use lowercase with hyphens for multi-word folders
- Use descriptive, searchable names
- Group related content logically

**Variables/Placeholders:**
- Use square brackets: `[PROJECT-NAME]`
- Use uppercase for major variables: `[TOPIC]`
- Use descriptive placeholder names: `[competitor-1]`

## VS Code Workspace Configuration

**Create [project-name].code-workspace:**
```json
{
    "folders": [
        {
            "path": "."
        }
    ],
    "settings": {
        "files.associations": {
            "*.md": "markdown"
        },
        "markdown.preview.fontSize": 14,
        "markdown.preview.lineHeight": 1.6,
        "explorer.sortOrder": "foldersNestsFiles",
        "files.exclude": {
            "**/.DS_Store": true,
            "**/Thumbs.db": true
        },
        "search.exclude": {
            "**/node_modules": true,
            "**/*.code-search": true
        }
    },
    "extensions": {
        "recommendations": [
            "yzhang.markdown-all-in-one",
            "shd101wyy.markdown-preview-enhanced",
            "bierner.markdown-mermaid",
            "davidanson.vscode-markdownlint"
        ]
    }
}
```

## Automation Scripts Template

**Python Data Analysis Script Template:**
```python
#!/usr/bin/env python3
"""
[PROJECT NAME] - [SCRIPT PURPOSE]
Analysis script for processing [TYPE] data

Usage: python3 script_name.py
"""

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from pathlib import Path

def load_data(file_path):
    """Load and clean raw data"""
    # Implementation here
    pass

def analyze_segments(df):
    """Perform segment analysis"""
    # Implementation here
    pass

def generate_insights(df):
    """Generate key insights and findings"""
    # Implementation here
    pass

def create_visualizations(df):
    """Create charts and graphs"""
    # Implementation here
    pass

def export_results(results):
    """Export analysis results"""
    # Implementation here
    pass

def main():
    """Main analysis workflow"""
    # Load data
    # Analyze
    # Generate insights
    # Create visualizations
    # Export results
    pass

if __name__ == "__main__":
    main()
```

## Usage Instructions for AI Agents

### Prompt Template for AI Agent:

```
Please create a comprehensive strategic analysis project structure for [TOPIC/INDUSTRY] following this template:

1. **Replace all placeholders** in square brackets with topic-specific terms:
   - [PROJECT-NAME] → [Your specific project name]
   - [TOPIC] → [Your topic/industry]
   - [competitor-1], [competitor-2] → [Actual competitor names]
   - [segment-1], [segment-2] → [Actual segment names]
   - [pain-point-1], [pain-point-2] → [Actual pain points]
   - [vertical-1], [vertical-2] → [Actual industry verticals]

2. **Create initial folder structure** with appropriate README files

3. **Populate key analysis files** starting with:
   - Main README.md with project overview
   - Segmentation overview
   - Competitive landscape overview
   - Pain point priority matrix template

4. **Customize for specific domain** by:
   - Adding domain-specific folders if needed
   - Modifying templates for industry requirements
   - Including relevant data sources and references

5. **Set up workspace configuration** for optimal VS Code experience

**Additional Context:**
- Primary focus: [Specify main analysis focus]
- Key stakeholders: [List main audience]
- Timeline: [Project duration]
- Data sources: [Available data sources]
```

### Example Implementation Command:

To implement this template for a new project:

1. **Create base directory**: `mkdir [project-name]`
2. **Copy template structure**: Use this template as reference
3. **Replace placeholders**: Find and replace all bracketed terms
4. **Initialize files**: Create README files and key templates
5. **Set up workspace**: Configure VS Code workspace file
6. **Begin analysis**: Start with customer segmentation or pain point analysis

## Best Practices

### Documentation:
- Keep README files updated with latest findings
- Use consistent formatting across all markdown files
- Include data sources and last updated dates
- Cross-reference related analyses

### Data Management:
- Keep raw data separate from processed data
- Document data transformation steps
- Version control important datasets
- Backup critical analysis files

### Analysis Workflow:
1. Start with customer segmentation
2. Identify pain points across segments
3. Analyze competitive landscape
4. Map solutions to pain points
5. Develop strategic recommendations

### Collaboration:
- Use clear folder structure for easy navigation
- Include explanatory README files
- Maintain consistent naming conventions
- Document assumptions and methodologies

## Customization Guidelines

This template can be adapted for various strategic analysis projects by:

1. **Adding domain-specific folders**:
   - Technology projects: Add `technology-stack/`, `architecture/`
   - Product analysis: Add `features/`, `roadmap/`
   - Market research: Add `trends/`, `forecasts/`

2. **Modifying analysis templates**:
   - Adjust segment criteria for different industries
   - Customize pain point categories
   - Adapt competitive analysis frameworks

3. **Scaling for project size**:
   - Small projects: Combine folders, simplify structure
   - Large projects: Add sub-categories, specialized folders
   - Multi-year projects: Add timeline-based organization

This template provides a solid foundation for systematic strategic analysis while remaining flexible enough to adapt to various topics and requirements.
