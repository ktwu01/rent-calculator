# rent-calculator

A tiny, dependency-free rent/utility split tracker. Pure HTML/CSS/JS, no build step, no server.

Open `index.html` directly in a browser, or serve it via GitHub Pages.

## What it does

This isn't a number calculator, it's a to-do generator: for each roommate, it tells you the one next action (they owe you, you owe them, or settled), not a raw number dump. Works for any number of roommates, not just one.

1. Add your roommates by name (saved locally, so you don't retype them every month).
2. List each item this month (rent, utilities, fees, internet, etc.), its amount, who fronted the cash, and how it splits: evenly among everyone in the house, or wholly as one specific person's own cost (not shared).
3. Pick Chinese or English, click "What do I do next?".
4. Copy the generated message(s) and send them. You act as the household's clearinghouse: each roommate settles directly with you, so the app gives you one line per roommate.

Example output (Chinese, you fronted everything, split evenly with one roommate):

```
光勇，你欠我857.65，麻烦Zelle给我。🙏感谢
```

Example output (English, 3 people, mixed fronting):

```
Hi Alex, you owe me 540.00. Please Zelle it to me. 🙏 Thanks!
Hi Sam, you owe me 630.00. Please Zelle it to me. 🙏 Thanks!
```

Everything runs client-side. No data is sent anywhere.
