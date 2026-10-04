# EverGesture MCP launch copy

## Directory title

EverGesture — thoughtful gifting and life-occasion planning for personal AI agents

## Short description

Remember the people and moments that matter, compare gifts or flowers, and prepare approval-safe next steps through a secure remote MCP server.

## Long description

EverGesture gives personal AI agents secure tools for birthdays, anniversaries, weddings, graduations, baby showers, religious holidays, condolences, hospital flowers, reminders, gift history, recipient preferences, and delivery coordination. It ranks options by recipient and occasion fit, total delivered cost, delivery confidence, seller reliability, policy terms, and freshness—not affiliate compensation. Every purchase, message, booking, or delivery requires separate explicit approval of the exact item, recipient, address or delivery method, timing, fees, and card message.

Endpoint: `https://occalyn-mcp-gateway.navureli.workers.dev/mcp`

Learn more: https://www.evergesture.com

## Reddit: r/mcp

**Title:** EverGesture MCP: approval-safe gifting and occasion planning for personal AI agents

I built EverGesture, a remote Streamable HTTP MCP server that helps personal AI agents remember occasions, compare thoughtful gifts or flowers, and prepare delivery plans without making an external commitment on the user's behalf.

The server supports OAuth 2.1 and dynamic client registration. Recommendations are ranked by recipient fit, occasion fit, delivered cost, delivery confidence, seller reliability, policy terms, and freshness—not affiliate compensation. Purchases, messages, bookings, and deliveries require separate approval of the exact details.

Endpoint: `https://occalyn-mcp-gateway.navureli.workers.dev/mcp`

Website: https://www.evergesture.com

I would value feedback on the tool boundaries, approval model, and client interoperability.

## Reddit: r/ClaudeAI

**Title:** I built an approval-safe MCP for gifts, flowers, reminders, and life occasions

EverGesture lets an AI assistant help with birthdays, anniversaries, weddings, graduations, condolences, hospital flowers, and other meaningful moments. It can organize confirmed preferences, compare options, and prepare the next step—but it cannot purchase, message, or deliver without a separate approval of the exact details.

It is available as a remote Streamable HTTP MCP server with OAuth 2.1:

`https://occalyn-mcp-gateway.navureli.workers.dev/mcp`

More details: https://www.evergesture.com

## Hacker News

**Title:** Show HN: EverGesture – an approval-safe MCP for gifting and life occasions

EverGesture is a remote MCP server for personal AI agents. It helps organize confirmed people, occasions, preferences, and gift history; compare gifts or flowers; and prepare approval-ready delivery plans.

The main design constraint is that recommendations and external action are separate. EverGesture cannot purchase, send, book, publish, or contact anyone until the user approves the exact item, recipient, delivery details, timing, fees, and card message. Fulfillment approvals are validated server-side, single-use, and expire after 15 minutes.

It uses Streamable HTTP and OAuth 2.1 with dynamic client registration.

MCP endpoint: `https://occalyn-mcp-gateway.navureli.workers.dev/mcp`

Website: https://www.evergesture.com

Feedback on MCP interoperability and the approval model would be especially useful.
