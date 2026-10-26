# InfrOS for Cursor

InfrOS designs cloud architectures from your requirements and generates the Terraform to deploy them. This plugin connects Cursor to InfrOS, so Cursor's agent can work in InfrOS as you: create projects and specifications, run designs, review the proposals, and read the generated Terraform.

## Install

Install **InfrOS** from the Cursor Marketplace.

Or add it to your `mcp.json` yourself:

```json
{
  "mcpServers": {
    "infros": {
      "url": "https://api.app.infros.io/assistant/mcp"
    }
  }
}
```

You need an InfrOS account at [app.infros.io](https://app.infros.io).

## Sign in

The first time Cursor uses InfrOS, your browser opens the InfrOS sign-in. After you sign in, InfrOS shows what Cursor is asking for and where the sign-in returns. Nothing is shared until you click **Allow**. Cursor then works as you: it sees and does only what your role in your organization allows.

## What Cursor can do

| Permission | What it allows |
| --- | --- |
| Read | See your projects, versions, landing zones, proposals and generated Terraform, and get the price of a design run or a Terraform generation |
| Write | Create projects and versions, and edit your drafts |
| Spend credits | Start a design run or a Terraform generation |
| Admin (organization admins only) | Manage your organization's landing zones, standing constraints and GitHub repository analyses |

## Credits

Design runs and Terraform generation use your organization's InfrOS credits. InfrOS gives the price first, and a start goes through only at that exact price. InfrOS tells Cursor to ask you before it spends.

## Stop access

In InfrOS, open your profile, find **Connected assistants**, and click **Revoke** next to Cursor. Cursor loses access within five minutes.

## Privacy and support

- Privacy policy: https://app.infros.io/privacy-policy
- Terms of service: https://app.infros.io/terms-of-service
- Support: support@infros.io
