# Koalaboox

Koalaboox is a Belgian cloud invoicing and cash-flow platform for small businesses,
self-employed professionals and their accountants. It now operates as **Cegid Invoice &
Financing** — API brand **Cegid Click & Finance** — following its acquisition by Cegid.

The platform covers sales invoicing, quotes, purchase-invoice management, recurring
invoices, dynamic dashboards, bank-account connections and Peppol-based electronic
invoicing for the Belgian 2026 e-invoicing mandate, sold in Belgium and Spain. Alongside
the SaaS it offers invoice financing — cash advances against outstanding invoices —
underwritten by Cegid Fin Belgium.

## API

- Developer portal: https://developers.cegid.be/ (Stoplight, formerly developers.koala.eu)
- Base URL: https://connect.koalaboox.com
- Auth: OAuth 2.0 authorization code, bearer access tokens + refresh tokens
- Reference implementation: https://github.com/koalaboox/api-refarch (Laravel, MIT)

The API host `connect.koalaboox.com` is still live under the Koalaboox name even though
the marketing and application hosts have moved to Cegid domains. No OpenAPI definition is
publicly retrievable — the Stoplight workspace is locked and its reference nodes return
404 — so the artifacts in this repo are grounded in first-party source code and live
endpoint probes rather than a harvested spec.

Backed by: speedinvest
