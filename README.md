# Tally

A small expense tracker that tells you when something doesn't add up.

**Try it:** [kdanieldann.github.io/tally](https://kdanieldann.github.io/tally/)

- Log expenses by date, merchant, category and amount
- See what you've spent, what's left of a monthly budget, and where it went by category
- Rows are flagged when they look wrong:
  - **possible duplicate**: same merchant and amount within three days
  - **unusual amount**: more than five times the usual spend in that category

Everything is stored in your browser (localStorage). No account, no server. "Reset demo data" brings back the sample month.

## Run locally

It's one HTML file. Open `index.html`, or serve the folder:

```
python3 -m http.server
```

Built with Claude Code.
