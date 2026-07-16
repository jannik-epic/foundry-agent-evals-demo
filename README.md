# Foundry agent evals demo

Runs the [microsoft/ai-agent-evals](https://github.com/microsoft/ai-agent-evals)
GitHub Action against an agent in Microsoft Foundry on every push to `evals/`.

The workflow signs in to Azure with OIDC (no secrets), sends the conversation
starters from `evals/intune-helpdesk.json` to the agent, and writes the
evaluation results to the run summary.

Demo repository for the book *Microsoft Foundry: The A-to-Z Guide to Building
and Governing Enterprise AI Agents*.
