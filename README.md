# chitty-pkg-google-gmail

Chitty Workspace marketplace package — Read, search, and send emails via the Gmail API.

## Requirements

- [Chitty Workspace](https://github.com/MTPython406/Chitty-Workspace) (required)
- [Chitty SDK](https://github.com/MTPython406/chitty-sdk) (`pip install chitty-sdk`)

## Tools

| Tool | Description |
|------|-------------|
| `gmail_read` | List, search, and read emails from your Gmail inbox |
| `gmail_send` | Compose and send emails, reply to threads |

## Features

- List recent inbox emails
- Search with full Gmail query syntax (`from:`, `subject:`, `is:unread`, etc.)
- Read full email content by message ID
- Send new emails and reply to existing threads
- OAuth 2.0 authentication via Chitty Workspace

## Installation

Install via the Chitty Workspace Marketplace tab, or manually:

```bash
# Clone into your Chitty marketplace directory
git clone https://github.com/MTPython406/chitty-pkg-google-gmail.git \
  ~/.chitty-workspace/data/tools/marketplace/google-gmail
```

## License

MIT — see [Chitty Workspace](https://github.com/MTPython406/Chitty-Workspace) for full license.

Built by [DataVisions.ai](https://datavisions.ai) | [chitty.ai](https://chitty.ai)
