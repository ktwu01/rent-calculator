# rent-calculator

A tiny, dependency-free rent/utility split tracker. Pure HTML/CSS/JS, no build step, no server.

Open `index.html` directly in a browser, or serve it via GitHub Pages.

## What it does

This isn't a number calculator, it's a to-do generator: for each roommate, it produces one itemized, self-explanatory message (what was paid, by whom, the arithmetic, and the final amount), so the recipient can see exactly why they owe what they owe, not just a bare number. Works for any number of roommates, not just one.

1. Add your roommates by name (saved locally, so you don't retype them every month).
2. List each item this month (rent, utilities, fees, internet, etc.), its amount, who fronted the cash, and how it splits: evenly among everyone in the house, or wholly as one specific person's own cost (not shared).
3. Pick Chinese or English, click "What do I do next?".
4. Copy the generated message(s) and send them. You act as the household's clearinghouse: each roommate settles directly with you, so the app gives you one itemized message per roommate.

Example output (Chinese, you fronted everything, split evenly with one roommate):

```
光勇，Rent+utility 1,639.96 usd + transaction fee 10.00 usd + spectrum 65.33 usd，这些都是我付，一共是1,639.96+10.00+65.33=1,715.29，你给我一半（1,715.29/2=857.65）就可以。🙏感谢，麻烦Zelle给我
```

Example output (English, 3 people, mixed fronting):

```
Hi Alex, this month's costs: Rent 1,800.00 usd (You paid), Internet 90.00 usd (Alex paid). Total 1,890.00 split 3 ways, your share is 1,890.00/3 = 630.00, so you owe me 540.00. 🙏 Thanks! Please Zelle it to me.
Hi Sam, this month's costs: Rent 1,800.00 usd (You paid), Internet 90.00 usd (Alex paid). Total 1,890.00 split 3 ways, your share is 1,890.00/3 = 630.00, so you owe me 630.00. 🙏 Thanks! Please Zelle it to me.
```

Everything runs client-side. No data is sent anywhere.
