# rent-calculator

A tiny, dependency-free rent/utility split calculator. Pure HTML/CSS/JS, no build step, no server.

Open `index.html` directly in a browser, or serve it via GitHub Pages.

## What it does

1. Enter who paid and their Zelle handle.
2. List each item you paid (rent, utilities, fees, internet, etc.) and its amount.
3. Set the other person's share (default 50%).
4. Pick Chinese or English, click "Generate message".
5. Copy the generated message and send it.

Example output (Chinese, 50% split):

```
光勇，Rent+utility 1,639.96 usd + transaction fee 10.00 usd + spectrum 65.33 usd，这些都是我付，一共是1,639.96+10.00+65.33=1,715.29，你给我一半（1,715.29/2=857.65）就可以。🙏感谢，我的Zelle是ktwu@utexas.edu
```

Everything runs client-side. No data is sent anywhere.
