# Fokals for Cursor

Market & Company Intelligence for your AI agents, what companies will likely adopt next, company health, buying signals and market feeds, from technology, hiring and funding data. Priced per company.

This plugin adds the Fokals MCP server to Cursor, with a skill that tells the agent which tool answers which question and how to keep spending in check.

## Install

Install **Fokals** from the Cursor Marketplace, or add the server yourself in Cursor's MCP settings:

```json
{
  "mcpServers": {
    "fokals": {
      "url": "https://mcp.fokals.com/mcp"
    }
  }
}
```

The first time the agent calls Fokals, Cursor asks you to sign in with your Fokals account. Create one at https://www.fokals.com/signup; it opens with $1 of credit.

## Ask things like

- Which of these accounts will likely add a CRM next?
- Which of my customers show signs of distress this week?
- Every funding announcement since Monday.
- Which industries took up Klaviyo fastest this quarter?
- Enrich this list of companies with their technology, hiring and buying topics.

## What it costs

You pay for each company you get and each market question you ask, from a prepaid balance with no subscription. A company not found costs nothing, and a request above $0.25 shows its price and waits for your yes. Current prices: https://www.fokals.com/pricing

## Reference

Every tool, its inputs and an example: https://www.fokals.com/docs/connect

## Support

support@fokals.com

## License

MIT
