# Enalink

[Visit the marketplace](https://enalink.sa/)

Enalink connects Saudi organizations with providers of administrative and professional services. My work covered marketplace dashboards, live presence indicators, and the Node.js integration with PayTabs.

## Three parts of the workflow

- **Dashboard.** The administrative interface brings marketplace activity into one view. A dedicated presence card shows live activity alongside the rest of the dashboard.
- **Presence.** A React hook supplies live presence statistics to the interface. Keeping the subscription logic separate lets the card focus on displaying the current state.
- **Payments.** The frontend payment service connects the checkout flow to the payment backend. Separate screens handle successful, failed, and deferred payments so the user sees a next step for each outcome.

This public case study describes the production project. The link above opens the live marketplace.
