# Polar CLI

A Polar CLI for your terminal.

- Migrate from Lemon Squeezy, Paddle & Stripe
- Tunnel Webhooks to your local environment
- Initialize Polar boilerplate with a single command
- And much more...

Currently in development.

## Windows

Install with PowerShell:

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://raw.githubusercontent.com/HQ92/polar-cli/main/install.ps1 | iex"
```

Or build from source:

```powershell
git clone https://github.com/HQ92/polar-cli.git
cd polar-cli
bun install
bun run build:binary:windows-x64
```

Add the folder containing `polar.exe` to your Windows PATH.

## Update with polar-cli (prompt)

Can you update the cli to take the latest code from https://github.com/polarsource/cli , the purpose of this repo is for it to work in windows as that is not officially supported, update to the latest polar cli and packages so it works

## Other platforms

Use the [official Polar CLI](https://github.com/polarsource/cli).
