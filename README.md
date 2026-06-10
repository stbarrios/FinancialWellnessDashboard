# Financial Wellness Dashboard

An interactive personal finance tracker that scores your financial health across 8 key KPIs — no backend, no login, no data ever leaves your browser.

## Features

- **8 KPI cards** — net worth, savings rate, emergency fund coverage, debt-to-income ratio, passive income ratio, housing ratio, credit score, and credit utilization
- **Wellness score** — a single 0–100 score with color-coded feedback
- **Budget doughnut chart** — visual breakdown of savings, housing, debt, and other expenses
- **KPI gauge bars** — at-a-glance progress toward each target
- **Live updates** — all metrics recalculate instantly as you type
- **Dark mode** — respects your system preference
- **Mobile responsive** — works on any screen size

## Usage

Just open `index.html` in any browser. No install, no server, no dependencies to manage.

Enter your numbers in the left sidebar and everything updates in real time.

## KPI Benchmarks

| KPI | Target |
|---|---|
| Savings rate | ≥ 20% |
| Emergency fund | 3–6 months of expenses |
| Debt-to-income | ≤ 36% |
| Housing ratio | ≤ 28% of gross income |
| Credit score | 740+ |
| Credit utilization | ≤ 10% |
| Passive income ratio | Trending toward 100% |

## Deploying

This is a single static HTML file — it can be hosted anywhere:

- **GitHub Pages**: Settings → Pages → Deploy from `main` branch
- **Netlify**: Drag and drop the file at `app.netlify.com/drop`
- **Vercel**: Import the repo at `vercel.com`

## Tech

Plain HTML, CSS, and JavaScript. Chart.js for the doughnut chart. No frameworks, no build step.
