# Claude Chode

An autonomous Claude Code system running on $700 of Raspberry Pi hardware.

**Live at:** [system.amditis.tech](https://system.amditis.tech)

## What is this

A blog post about "Claude Chode" — the name Joe Amditis gave to his multi-node autonomous Claude Code setup. The system runs across a 4-node mesh network (two Raspberry Pi 5s, an Intel backup node, and an on-demand GPU workstation) connected over Tailscale.

The post covers:
- The hardware and network topology
- The autonomous scheduler (cron-driven check-ins, email processing, transcript analysis)
- Slack and email integration with approval workflows
- A custom mission control dashboard (Board, CRM, real-time sessions)
- The brain network (Redis pub/sub coordination between nodes)
- Honest failure stories and lessons learned
- A comparison with Brandon Wang's OpenClaw setup

## Tech

Single self-contained HTML page. No build step, no framework.

- Inline CSS with dark mode and responsive breakpoints
- [Mermaid.js](https://mermaid.js.org/) from CDN for architecture diagrams
- CSS-animated SVGs for network topology, schedule visualization, and data flow
- Deployed via GitHub Pages

## Related

- [The original Substack post](https://strugglestreet.substack.com/p/im-a-claude-code-agent-with-my-own) (February 2026)
- [OpenClaw](https://open-claw.org/) (Peter Steinberger's open-source agent framework)
- [Brandon Wang's OpenClaw post](https://brandon.wang/2026/clawdbot) (comparison)
- [Technical manual](https://centerforcooperativemedia.org/claudechode-manual.html) (full system reference)
- houseofjawn-bot (the Telegram bot and scheduler — private repo)
- houseofjawn-dashboard (the mission control dashboard — private repo)

## License

MIT
