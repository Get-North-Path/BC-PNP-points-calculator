# Privacy

This page records only the privacy and contact behavior that is **visible on the public BC PNP site** or on the policy pages that site links to. It does not describe private API routes, server logs, or analytics configuration. `robots.txt` disallows `/api/`. [llms.txt](https://bcpnp.getnorthpath.com/llms.txt) says private `/api/*` routes are not for indexing. Those routes are not part of this documentation.

Live calculator: [bcpnp.getnorthpath.com](https://bcpnp.getnorthpath.com/)

Policies linked in the site footer:

- [Privacy](https://www.getnorthpath.com/privacy)
- [Terms](https://www.getnorthpath.com/terms)

The footer also states: **Not affiliated with the Government of British Columbia, WelcomeBC, or IRCC.** The bottom line says **© GetNorthPath · Not legal advice.**

---

## Running an estimate

The calculator asks for category, employer type, whether the offer is indeterminate and full-time, hourly wage, an illustrative median, region, months of experience, education, a credential flag, a designation flag, four CLB levels, and an Express Entry checkbox.

No account is required to see a score.

This repository does **not** claim that those inputs stay only in the browser. The public pages do not state a client-only processing guarantee for the score itself. They do state what the consultation form is for, below.

Do not send identity documents, passport numbers, or full application files through the score form. The document checklist is a preparation guide. The calculator does not upload those documents.

---

## Consultation form on the calculator

Section: [bcpnp.getnorthpath.com/#consultation](https://bcpnp.getnorthpath.com/#consultation)

The heading is “Request a free consultation.” The description says: “Attach your category and score and talk through your options with an advisor.”

| Field | Required on the form | Notes |
| --- | --- | --- |
| Full name | Yes | Text field |
| Email address | Yes | Email field |
| Phone | No | Placeholder: “Phone (optional)” |
| Category and score | Attached by the page | Read-only text such as “Category: Care: Health · Score: 0 / 200”. Not a separate field you type |

The note under the button says: **“Your category and score are attached automatically.”**

The button label is “Request my free consultation →”.

This hub does not document the submission endpoint.

---

## Walkthrough link

The header “Book a walkthrough” control goes to the parent site:

[getnorthpath.com/contact?intent=walkthrough&tool=bc-pnp-calculator#book](https://www.getnorthpath.com/contact?intent=walkthrough&tool=bc-pnp-calculator#book)

That page is GetNorthPath’s contact flow, not a second calculator. Anything submitted there is covered by the parent [privacy](https://www.getnorthpath.com/privacy) and [terms](https://www.getnorthpath.com/terms) links the BC PNP footer uses.

The footer “Book a free call” item points at the on-site consultation section, not at that parent URL.

---

## What this product does not do with your information

The public site does not say that:

- an estimate creates a SIRS registration
- an estimate files a Skills Immigration application or an IRCC application
- GetNorthPath reviews or signs an immigration application
- the consultation form is an official WelcomeBC channel

---

## This repository

The documentation repository contains product explanations and public images from the live site (the Open Graph card and screenshots of public pages). It does not contain consultation submissions, calculator answers from visitors, application source code, credentials, or private URLs.
