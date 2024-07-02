## iFrame Integration

[Some description about why to integrate via iFrame, easy / minimal setup or something like this]

To customise the iFrame integration, see [page about query parameters, including locked parameters]

The parent window can be notified of status updates via event listeners.

```typescript
window.addEventListener(
  "message",
  (event: MessageEvent) => {
    if (event.origin !== "https://swap.boomfi.xyz") {
      return;
    }

    // Use event.data
    switch (event.data.status) {
      case "pending":
      case "failed":
      case "success":
    }
  },
  false
);
```

Example payload

```json
{
  "data": {
    "id": "2ieU2MDpE0AxK8n0501xToOHs5d",
    "parent_id": "",
    "org_id": "2Tpmnmh6GHJXumKN1oBy2u56Ima",
    "amount": "100",
    "currency": "EUR",
    "invoice_id": "",
    "source": "BoomFi",
    "payment_method": "Ramp",
    "customer_id": "2f02b8uYRvksofOnd2Pn1Rlyeqm",
    "status": "RequiresAction",
    "next_action": "pay_2ieU2FNcx300EdVVbG8nw2okFkv",
    "scheduled_time": 0,
    "created_at": "2024-07-01T16:12:07.112Z",
    "updated_at": "2024-07-01T16:12:07.401Z",
    "customer": {
      "id": "2f02b8uYRvksofOnd2Pn1Rlyeqm",
      "org_id": "2Tpmnmh6GHJXumKN1oBy2u56Ima",
      "name": "",
      "email": "checkout@boomfi.xyz",
      "phone": "",
      "wallet_address": "",
      "deleted_at": null,
      "reference": "user-test-0da23b11-1692-40a8-9ca4-3b974f5747de",
      "metadata": "e30=",
      "properties": "e30=",
      "v1": "e30=",
      "created_at": "2024-04-12T12:09:02.905Z",
      "updated_at": "2024-04-12T12:09:02.905Z"
    },
    "properties": {
      "amount_usd": "107.2261879306286",
      "ramp": {
        "buy_currency": "USDC",
        "buy_currency_amount": "95.9",
        "buy_token": "0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48",
        "buy_token_chain_id": 1,
        "customer_payment_method": "Card",
        "customer_settlement_address": "0x844Acef789989Cb6E21E0F07DD4e894709f92F96",
        "fees": {
          "boomfi_fee": "1",
          "fee_ccy": "EUR",
          "network_fee": "5.61569026275441533820131343",
          "total_fee": "6.61569026275441533820131343"
        },
        "rate": "1.0269",
        "sell_currency": "EUR",
        "sell_currency_amount": "100"
      },
      "test_mode": true
    }
  }
}
```
