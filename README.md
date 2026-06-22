# n8n-support-agent-workflow
# Build a Lean AI Agent Workflow in n8n Using APIs, Webhooks, and JSON

## Workflow
Webhook (POST) → AI Agent → Open AI Chat Model

## Description
This workflow receives user requests through a Webhook, processes input in JSON format, and uses Open AI via the AI Agent node to generate responses in real time.

## Technologies Used
- n8n
- Webhooks
- JSON
- Open AI Chat
- AI Agent Node

## Example Input
{
  "message": "My order hasn't arrived yet."
}

## Example Output
"Sorry — I can help. To look into this I just need a bit of info:\n\n- Order number (or the confirmation email address)\n- Date you ordered\n- Shipping address (or last 4 of the ZIP)\n- Tracking number (if you have it)\n\nIf you prefer to check quickly yourself, try these steps first:\n1. Find the shipping/tracking email from us and click the carrier tracking link.  \n2. Check the carrier’s site for the latest status and estimated delivery window.  \n3. If tracking says “delivered” but you don’t have it, check around your property, ask neighbors or front desk, and look for a photo or delivery notes.  \n4. If tracking shows delay or “in transit,” wait 24–48 hours for updates; carriers sometimes update late.  \n5. If it appears lost or misdelivered, reply here with the info above and I’ll open an investigation or request a refund/replacement for you.\n\nIf you share your order number or tracking now, I’ll check the status and tell you the next steps."
