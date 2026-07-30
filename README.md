# rent-calculator

A tiny, dependency-free rent/utility split tracker. Pure HTML/CSS/JS, no build step, no server.

Open `index.html` directly in a browser, or serve it via GitHub Pages.

## What it does

This isn't a number calculator, it's a to-do generator: it tells you the one next action to take (send a Zelle request, or send money yourself), not just a total.

1. Pick this month's pattern: "I pay for all", "Roommate pays for all", or "Custom" (mix per item).
2. List each item (rent, utilities, fees, internet, etc.), its amount, and who paid it (per-item, editable even after picking a preset).
3. Pick Chinese or English, click "What do I do next?".
4. Copy the generated message and send it. Split is always even (50/50); the message tells you who owes whom, based on what each person actually paid.

Example output (Chinese, "I pay for all"):

```
光勇，Rent+utility 1,639.96 usd + transaction fee 10.00 usd + spectrum 65.33 usd，这些都是我付，这个月一共1,715.29，你给我857.65（1,715.29-857.65=857.65）就可以。🙏感谢，我的Zelle是ktwu@utexas.edu
```

Everything runs client-side. No data is sent anywhere.
