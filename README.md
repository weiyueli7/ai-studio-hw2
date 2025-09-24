# LangChain Pirate Agent

This agent wraps `langchain_pirate.py`, which spins up a Nanda adapter service connected to Anthropic's Claude 3 Haiku. Incoming chat messages are routed through a LangChain prompt that rewrites them into pirate-sounding English while keeping the original intent. The service starts a local development server by default, and can switch to the adapter's SSL-enabled API mode when a `DOMAIN_NAME` is configured.

## Feedback on the Adapter

- The deployment walkthrough in the adapter [README](https://github.com/projnanda/adapter), especially [this section](https://github.com/projnanda/adapter?tab=readme-ov-file#deploy-from-scratch-on-a-barebones-machine-ubuntu-on-linode-or-amazon-linux-on-ec2), was the clearest path for getting the agent running. Highlighting or surfacing that section earlier could save new users time.
- The Nanda Registry site was intermittently unavailable, so I captured a log file with the registration callback URL instead. This should satisfy the homework requirement in lieu of a registry screenshot according to the TA guidelines.


