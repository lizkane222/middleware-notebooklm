This is a comprehensive Middleware Template Guide (MIDDLEWARE_TEMPLATE_GUIDE.md) that you can share with AI agents to automate the creation of future middleware testing pages.
What's Included:

1. Architecture Overview
Visual diagram of the three-section structure
File organization breakdown
Component hierarchy

2. JavaScript Architecture (8 Parts)
Part A: Segment snippet (required, no changes)
Part B: Event Logger Middleware (required, copy as-is) ⭐
Part C: Custom middleware logic (customizable)
Part D: Debug functions (optional)
Part E: UI helper functions (required, copy as-is) ⭐
Part F: Test step functions (customizable)
Part G: Event trigger functions (recommended)
Part H: Initialization logic (required, minor customization) ⭐
Each part includes:
Line number references
Code examples
Purpose explanation
Customization guidance
Best practices

3. CSS Styling Guidelines
Two-column grid layout
Console log styling (critical - copy exactly)
Component styles
Color coding system

4. HTML Structure
Header format
Left column (test steps) with repeating templates
Right column (status + console)
Implementation guide section (new!)
Step design guidelines and typical flow

5. Key Patterns & Best Practices
Timeout fallback pattern (critical)
Event logger registration
IIFE scope isolation
Console logging prefix
Status panel updates

6. Template Checklist
Complete checklist organized by phase:
Setup (5 items)
Testing Interface (10 items)
Styling (4 items)
Implementation Guide (6 items)
Testing (7 items)

7. Common Middleware Types
Step patterns for:
URL parameter capture
Data enrichment
PII redaction
Consent management
Custom identity resolution

8. Must-Have Components Summary
Three tiers:
✅ Essential (every test)
✅ Recommended (most tests)
⚪ Optional (as needed)

9. AI Agent Prompt Template
Ready-to-use prompt structure for requesting new middleware pages, including:
Required information fields
Template constraints
Structure requirements

Key Strengths:
✅ Generalized - Removed GCLID-specific details
✅ Comprehensive - Covers every component and pattern
✅ Actionable - Includes code examples and checklists
✅ Visual - ASCII diagrams and structure outlines
✅ Flexible - Marks what's required vs. customizable
✅ Best Practices - Explains WHY, not just WHAT
✅ AI-Ready - Includes prompt template for automation

You can now share this guide with any AI agent and say:
"Create a middleware testing page following MIDDLEWARE_TEMPLATE_GUIDE.md for [middleware description]"




<!-- Add a section at the top of every new middleware HTML file which provides instructions for the VSCode CoPilot's AI Agent -->
<!-- This section should be required to be read by the AI Agent when making any code updates -->
<!-- The AI Agent should always ensure that the Implementation Guide section always stays aligned with any code updates made throughout the rest of the code. -->
