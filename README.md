# GrowthFlow · Commercial Decision-Support Workspace

This repository serves the public **synthetic** GrowthFlow demonstration. It does not contain customer information, a live CRM integration, or API credentials.

- Primary business date uses the visitor's local calendar date every time the application is opened or reloaded. When a previously opened tab is resumed on another day, the app refreshes its date-based calculations.
- Historic commercial records retain their recorded dates. A changing date does **not** mean CRM data was refreshed.
- Customer-fit assessments, account statuses and activity plans are calculated using the underlying demonstration records.
- The decision-watch card on Home is derived from the same Northline commercial case rules as the account-development workflow.

**Deployment:** Render Static Site, `main` branch, root directory blank, publish directory `.`. The static website lives at root `index.html`. Do not deploy the full source ZIP to a public web service.

**Testing:** The included full development source has Node business-rule checks and a Playwright standalone-browser regression script. Any public Render deployment requires its own final verification.
