# Auto Shop CFO — Free Calculators

A static, client-side calculator page for auto repair shops, in the same
style as [Electrician Business CFO](https://mundusflow.github.io/electrician-business-cfo/)
and [Freelance Tax & Runway Estimator](https://mundusflow.github.io/freelance-tax-runway-estimator/).
Plain HTML, CSS, and JavaScript — no build step, no backend, no data leaves the browser.

## Calculators

- **Quote Builder** — parts + markup, labor, shop supplies, and a profit buffer → a suggested repair estimate.
- **Job Profit Calculator** — invoiced amount minus actual parts/labor/other costs → profit and margin, with a low-margin warning under 15%.
- **Labor Rate Calculator** — monthly overhead (rent, insurance, equipment, software, other) + desired annual profit ÷ billable hours/year → minimum rate to charge.
- **Tax Reserve Calculator** — splits self-employment tax (15.3%) from a selectable federal income tax bracket, shown as a transparent profit × rate = reserve chain.
- **Business Runway Calculator** — savings ÷ monthly expenses → months of runway.

## Deploying

Push this folder to a new GitHub repo and serve with GitHub Pages
(Settings → Pages → deploy from the `main` branch), same as the other two projects.

## The paid workbook

The CTA section pitches the "Auto Shop CFO" Excel workbook (Dashboard, Repair
Orders, Quote Builder, Labor Rate, Parts Pricing, Technicians, Expenses, Cash
Flow, Profit & Loss, Settings). The `images/` folder holds two product
screenshots (Dashboard, Repair Orders) generated from a sample-data copy of
the real workbook.

**Not yet wired up**: the CTA button and sticky bar currently point at a
placeholder `mailto:you@example.com` link — replace with a real checkout link
once pricing and payment delivery are set up (see the Electrician Business
CFO project for the Stripe + Cloudflare Worker + R2 pattern already built
for that product, which can be extended to a third product the same way the
Freelance CFO was added).
