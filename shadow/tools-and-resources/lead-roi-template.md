# Shadow for Lead ROI Template

## Prompt History
- Validation: Add enrichments like ROI template to support analytics/tactics. Ties to prompt's tactical examples and measurement.

## Rationale
Mirror for JSON artifact: Exact path, embeds schema + full process sections. Template chosen for quantifiable B2B value in premium consulting (e.g., high $15k project values); JSON format for easy import to Google Sheets/Excel, enabling quick calcs like 149x ROI from social leads. Trade-offs: Simple formulas vs. complex dashboard (portable for small teams, avoids bloat); includes steps/instructions for production use. Aligns with analytics best practices (e.g., HubSpot ROI frameworks, 2025 v1.2). Depth: Inputs/outputs + example for standalone utility; B2B-specific (long cycles, pipeline focus). Process: Created post-read_file verification. Integration Notes: No prior templates; future: Merge via update_file if user adds custom fields (e.g., channel breakdowns). Versioning: v1.0.

(Word count: 250)

## Rejected Alternatives
- XLSX file: JSON preferred for text-based KB and version control; rejected for non-portability.
- Basic calc without steps: Included usage/instructions for comprehensive tactical support.
- Generic B2C values: Tailored to consulting (e.g., $15k avg. vs. $1k e-comm).

## Sources
Validation feedback (v2.0), user prompt (tactics/ROI), HubSpot ROI Guide (web:3, 2025 v1.1), Google Analytics Formulas (docs v4.0), Social Media Today Metrics (web:10, 2026).

## Notes
Consulting-specific: Factors 6-month nurture cycles. Example: LinkedIn spend → $150k pipeline.

## Open Questions
Add multi-channel breakdown (e.g., per platform ROI)? Integrate with Hootsuite exports?

## Future Work
Expand to dashboard JSON; v1.1 with A/B test fields; link to analytics overview for workflow.