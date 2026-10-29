# Jobs Data Intelligence for Gemini CLI

Live job listings from Greenhouse, Lever, Ashby, Workday, EURES, Reed, Wellfound, Y Combinator and remote boards.

This extension connects Gemini CLI to the hosted MCP server [Jobs Data Intelligence](https://mcpize.com/mcp/jobs-data-intelligence). It reads public pages only and needs no login or cookies for the source itself.

## Install

```
gemini extensions install https://github.com/benthepythondev00/jobs-data-intelligence
```

Gemini CLI asks for your MCPize API key once and keeps it in the system keychain.

## Get a key

1. Open https://mcpize.com/mcp/jobs-data-intelligence and subscribe. The Free plan needs no card.
2. Copy the API key shown on the server page.

## Try it

- "What is Stripe hiring for in Dublin right now?"
- "Find remote Python jobs on We Work Remotely and Himalayas."

## Plans

Billing runs through MCPize: Free for a small monthly allowance, Pro $9 for 1,000 calls, Business $29 for 5,000 calls. See the server page for the current numbers.

## Notes

Independent server by benthepythondev. Not affiliated with or endorsed by the sites it reads. The same data is available as Apify Actors: https://apify.com/benthepythondev
