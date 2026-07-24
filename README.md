# CloudPulse — Enterprise SaaS Landing Page & Subscription Portal

CloudPulse is a full-stack, enterprise-ready SaaS landing page and subscription management portal engineered with Next.js (App Router), Tailwind CSS, and Stripe API integration. It provides a complete end-to-end user acquisition flow. From landing page conversion to checkout, automated onboarding, and active subscription management.

### 🚀 Key Features
* **Dark Mode UI & Clean UX:** Native Tailwind dark theme with an interactive theme switcher.
* **Responsive Pricing Engine:** Dynamic billing cycle toggle (Monthly vs. Annual) integrated with Stripe Checkout session generation (`/api/checkout`).
* **Authentication Portal:** Dedicated sign-in route (`/login`) built for seamless portal access.
* **Subscription Management Dashboard:** Interactive management portal (`/dashboard`) displaying active plan tiers, next billing renewal dates, and payment method options.
* **Automated Email Onboarding:** Asynchronous API pipeline (`/api/onboarding`) triggering automated welcome emails and API key provisioning upon registration.

### 🛠️ Tech Stack
* **Framework:** Next.js 14 (App Router)
* **Styling:** Tailwind CSS, Lucide React Icons
* **Payments:** Stripe API & `@stripe/stripe-js`
* **Runtime:** Node.js (JavaScript / ES6+)
