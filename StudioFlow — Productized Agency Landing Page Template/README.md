# StudioFlow — Productized Agency Website Template

Thank you for purchasing **StudioFlow**! This is a fast, conversion-focused HTML5 + Tailwind CSS website template built specifically for productized agencies, design/dev subscriptions, video editing studios, and solo consultants.

## Included Files
* `index.html` — High-converting main landing page (Hero, Portfolio Showcase, 3-Step Workflow, Benefits, Subscription Pricing, Cal.com Booking CTA, and Interactive FAQ).
* `case-study.html` — Detailed client case study page with before/after comparison and conversion metrics.
* `legal.html` — Pre-written Terms of Service (including subscription pause/refund clauses) and Privacy Policy tailored for Stripe approval.
* `README.md` — This quick-start setup guide.

---

## Quick Customization Guide (Takes ~10 Minutes)

### 1. Change Your Brand Accent Color
Open `index.html`, `case-study.html`, and `legal.html`. Locate the `tailwind.config` script near the top of `<head>` and replace the hex codes with your own brand color:

```javascript
colors: {
  accent: {
    500: '#ff5500', // Primary accent color
    600: '#e04800', // Hover state color
  }
}