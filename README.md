# feedback.net

Website for **Feedback**, the agent reputation protocol in the AgentMesh family.

- **Spec repo:** https://github.com/jeffrschneider/feedback
- **Family sites:** [agentnaming.ai](https://agentnaming.ai) · [dev.agentmesh.ai](https://dev.agentmesh.ai)

## Pages

| Page | Purpose |
|---|---|
| `index.html` | What Feedback is — evidence → ledger → report |
| `why.html` | Why the mesh needs reputation; why star ratings fail |
| `evidence.html` | The three evidence classes and the outcome taxonomy |
| `scores.html` | Decay, the posterior, rank-on-LCB, UNPROVEN |
| `trust.html` | What a report proves, enrollment states, the attack table |
| `developers.html` | Canonical strings, the report wire format, L1/L2/L3 verification |

Static HTML + one stylesheet (`site.css`, THE WIRE design system shared with
agentmesh.ai and agentnaming.ai). No build step; serve the directory as-is.
