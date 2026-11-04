# BenefitLab 2027

An interactive, browser-based cost simulator for the **2027 Cedar Cares and Dell** medical plans.

## Open the website

Once GitHub Pages is enabled: **https://stryxzilla.github.io/benefitlab-2027/**

## Features

- Sliders for pediatric visits, urgent care, prescriptions, therapy, surgery and hospitalization
- Compare 12 family medical coverage arrangements, including mixed HDHP and PPO options
- See negotiated charges versus deductible, copays, coinsurance, total medical bills and premiums
- Explore which plan is cheapest and the PPO/HDHP break-even points
- Export comparisons and save scenario settings locally in your browser
- Responsive layout for desktop and mobile

## Deployment

This repository uses a self-contained **index.html** (inline CSS and JavaScript), with no npm install, external service, server, or API keys.

The GitHub Actions workflow at `.github/workflows/pages.yml` publishes the main branch to GitHub Pages. To activate it, open **Settings → Pages → Build and deployment → Source → GitHub Actions**. The deployment then runs automatically after each push to `main`.

## Privacy

The **website code is public**, but the simulator does not upload your medical inputs to a server; values and saved scenarios are handled inside your browser. Do not commit sensitive health records or personalized inputs to this public repository.

## Limitations

Plan terms were transcribed from employer-provided 2027 documents. All scenario charges are illustrative estimates, **not claims adjudications or network price guarantees**. Confirm actual providers, covered services, HSA eligibility, premiums and plan restrictions with your employers/insurers before enrolling.
