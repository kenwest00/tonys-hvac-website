# Synergy Heating & Cooling — Website

**Live site:** `index.html`

A high-converting, single-file HTML website for **Synergy Heating & Cooling**, serving the Atlanta metropolitan area.

## What’s in this repository

| File | Description |
|---|---|
| `index.html` | Full production website with all HTML, CSS, and JavaScript in one file |
| `synergy-heating-cooling-logo.png` and `.webp` | Synergy Heating & Cooling brand logo with optimized WebP delivery |
| `hero.png` and `.webp` | Atlanta-area hero image with optimized WebP delivery and PNG fallback |
| `favicon-32.png` / `apple-touch-icon.png` | Browser and mobile device icon assets |
| `synergy-growth-blueprint.docx` | Synergy growth strategy reference document |
| `README.md` | Project overview and implementation notes |

## Site sections

| Section | Purpose |
|---|---|
| Hero | Separates urgent service callers from visitors who want to research savings and system care |
| Trust bar | Communicates key credentials and service benefits |
| About Synergy | Introduces the company’s service standards, customer experience, and metro Atlanta focus |
| Services | Covers AC repair, installation, heating, maintenance, and handyman services |
| Savings section | Explains Synergy’s direct-service value proposition and quote-comparison story |
| Complimentary maintenance offer | Promotes an online-bookable HVAC maintenance session with a $200+ stated value |
| Maintenance details | Explains coil cleaning, refrigerant-performance checks, capacitor checks, blower-motor amperage checks, airflow review, and plain-English findings |
| Value in Action | Adds two clearly labeled illustrative service scenarios that explain how Synergy helps customers make informed comfort and repair-planning decisions |
| Service standards section | Builds trust through transparent company commitments and customer-first service principles |
| Testimonials, FAQ, and contact area | Supports conversion and answers common customer questions |

## Online maintenance booking

The online maintenance booking area has client-side required-field validation, truthful success/error states, and call-to-book fallback messaging. To activate production lead delivery, set the `data-formspree-endpoint` value on `maintenance-booking-form` to the business’s Formspree endpoint. Until this is configured, the site deliberately shows an actionable error state rather than a misleading success confirmation or silent data loss.

## Customization priorities

| Priority | Next change |
|---|---|
| 1 | Set the Formspree endpoint and confirm the business inbox receiving maintenance requests |
| 2 | Add the GA4 Measurement ID so `form_submit_success`, `form_submit_error`, and `phone_click` events are recorded |
| 3 | Confirm the exact complimentary maintenance scope, eligibility, service-area limits, and terms before launch |
| 4 | Replace the About visual placeholder with professional imagery of Synergy service work and equipment |
| 5 | Add verified Google Reviews or another independently verifiable review source before supplying an aggregate rating |

## Technology

The site is plain HTML, CSS, and JavaScript. It does not require a build process, framework, or third-party runtime dependency. Google Fonts provides Bebas Neue, Outfit, and DM Serif Display. It includes canonical/social metadata, HVACBusiness and FAQ JSON-LD, responsive WebP image delivery, favicon assets, and a mobile sticky call/book bar.

## Contact

**Synergy Heating & Cooling**

Atlanta Metropolitan Area

770-292-8989
