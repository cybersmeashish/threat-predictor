# Threat prediction and triage research

Research questions for AI-assisted security operations, linked to concrete control and evidence examples.

**Stage:** research notes. A trained prediction model, forecast quality, alert-reduction percentage, and deployed SOC are not established by this repository.

## Questions worth testing

| Question | Required experiment |
| --- | --- |
| Does contextual triage improve prioritization? | Labelled findings, analyst baseline, held-out evaluation, and error analysis |
| Can automation remain within approved authority? | Allowed/denied action fixtures, human approvals, and attributable decisions |
| Does a new detector help beyond its training data? | Time-separated evaluation, benign controls, and dataset-shift analysis |

## Working related material

- [Sovereign AI tool authorization and evidence](https://github.com/cybersmeashish/sovereign-AI).
- [Agent honeypot reference implementation](https://github.com/cybersmeashish/cybernonics_tools/tree/main/agent-honeypot).
- [AI service asset and action inventory](https://github.com/cybersmeashish/Ashish-research/tree/main/weeks/01-system-and-asset-inventory).

Publish measured results with source data and limitations before describing predictive performance.
