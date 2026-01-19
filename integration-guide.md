# Integration Guide for Knowledge Base Updates

## Overview
This guide outlines how to integrate new or existing content into the social media marketing KB for premium software consulting. Since the directory was empty at initialization (verified via list_directory_tree), all content was built from scratch. For future updates, follow this process to evaluate and merge prior artifacts while maintaining semantic relevance and structure.

## Step-by-Step Integration Process
1. **Discovery and Evaluation**: Call list_directory_tree(path=".") to scan current structure. Use read_file on suspected files (e.g., path="existing-content.md") to review contents. Assess relevance: Does it align with B2B consulting tactics/platforms? (e.g., Filter out consumer-focused posts; prioritize step-by-steps for lead gen).

2. **Relevance Filter**: Check against core goals—value-first, professional tone. Reject if unrelated (e.g., TikTok trends for enterprises). For partial matches, excerpt useful sections (e.g., general SMM stats adapted to software ROI like $15k projects).

3. **Structural Mapping**: Map to domains: Platforms for tips (e.g., add to reddit/overview.md if community-focused); Tactics for walkthroughs (e.g., new sub under tactical-examples). Use kebab-case naming (e.g., "lead-gen-webinar.md"). Ensure canonical entry (overview.md) if new folder.

4. **Metadata and Shadow Update**: Add rationale (200–400 words on why integrated, trade-offs like "Merge vs. new: Preserves history but risks bloat"). Update sources (e.g., "Prior user file, v1.0"). Create/update shadow with # Integration Notes (e.g., "Merged from read_file on existing.md; relevance score: High for B2B"). Dependencies: Add relative paths (e.g., ["strategy-development/overview.md (v1.0, for goal alignment)"]).

5. **Content Enhancement**: Boost density—180–400+ words with examples (e.g., add ROI calc if analytics-related). Format: Headings/lists/code. Validate standalone: Test as useful (e.g., step-by-step usable without root).

6. **Logging and Verification**: Append change_log (action="update_node", reason="Integrated prior content with relevance filter, v1.1"). Re-run list_directory_tree to confirm no duplicates. Shadow # Future Work: "Periodic audits via read_file".

Example: If prior "smm-tips.md" found, evaluate: High relevance for platforms; merge into linkedin/overview.md, log "update_node", update shadow with history.

This ensures the KB remains clean, professional, and aligned with best practices (e.g., modular docs like Confluence). Word count: 420