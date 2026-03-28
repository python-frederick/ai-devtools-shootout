# ai-devtools-shootout

A repo to compare devtools used by Python Frederick members

## Questions to answer

- Is this a UI or terminal experience? What is the UX?
- What is the permission and security model?
- How do you extend it and what is the ecosystem?
- Is it closed or open source?
- What is the payment model?
- What is the resource footprint?
- What programming languages can you use? Any restrictions?

## Chris - VS Code / Copilot

[Code - OSS](https://github.com/microsoft/vscode) - Open source base

[VS Code](https://code.visualstudio.com/) - What you're looking at right now

### UX

Full featured GUI akin to it's big brother, Visual Studio.

Integrated terminal for command line work or those who prefer certain command line tools/interactions.

### Permissions and Security

Copilot is fairly locked down by default, requesting permission for basically anything that is not just editing a file in the current workspace.

Allows for YOLO mode, but in my experience it never wanders outside of the current workspace. Perhaps M$sft has some hidden sandboxing or something?

### Extensibility and Ecosystem

Massive extension marketplace, including support for:

    - New languages/Linters/Formatters
    - Live environments (e.g. Jupyter notebooks or http servers)
    - AI tools
    - GitHub integrations

Allegedly some are paid, never seen one myself.

***Caveat***: Extensions are not 100% compatible between Code - OSS and VS Code, but overwhelmingly they are.

### Open or Closed Source

Interesting combination!

What you're looking at is 'VS Code', closed source, developed and published by Microslopt

'VS Code' is actually just a closed fork of 'Code - OSS', which is open source and available on GitHub. Per the OSS readme:

> Visual Studio Code is a distribution of the Code - OSS repository with Microsoft-specific customizations released under a traditional Microsoft product license.

Microslopt actually does all their development with the community on the Code - OSS repo, then presumably merges it into their closed source fork.

### Payment Model

Both VS Code and Code - OSS are free to use

Copilot has a free tier but still requires an account with GitHub. Paid tier starts at $10/month or $100/year.

### Resource Footprint

Touted as the 'lightweight' code editor, but it is still a full development environment

More extensions can also really drag down performance.

### Programming Languages

If it has an extension, you can use it.

All common languages are supported, some more niche ones may be missing features or have less support. Like all open source projects, the ecosystem is driven by the community, so languages with more users will have better support.

## David

Claude Code (or Codex)

## Ben

opencode

## Matt

opencode
