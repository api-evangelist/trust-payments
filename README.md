# Trust Payments (trust-payments)

Trust Payments is a London-headquartered payment gateway and processor (formerly Secure Trading / SecureTrading) operating across the United Kingdom, Europe, and the United States. It provides online, point-of-sale, unattended, and mobile card acceptance, acquiring, alternative and local payment methods, tokenisation, recurring billing, payouts, and 3-D Secure authentication through its TRU Connect gateway.

Its developer surface is the Secure Trading Payment Platform (STPP): a server-to-server JSON Webservices API, a JWT-authenticated client-side JavaScript Library for PCI-reduced hosted card fields, and mobile SDKs. Documentation is published as reference articles in the Trust Payments help centre, with Python, PHP, ReactJS, and Swift libraries under the SecureTrading GitHub organisation. Trust Payments does not publish a downloadable OpenAPI/Swagger definition, and production Webservices access requires PCI certification, account approval, and credential exchange.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/trust-payments/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/trust-payments/refs/heads/main/apis.yml)

## Tags

- Payments
- United Kingdom
- Payment Gateway
- Payment Processing
- Acquiring
- Card Payments
- Tokenization
- Subscriptions
- 3-D Secure
- Point of Sale

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### Trust Payments Webservices API

Server-to-server JSON API (the Secure Trading Payment Platform / STPP) for card processing and management on the TRU Connect gateway. Supports request types including AUTH, ACCOUNTCHECK, REFUND, SUBSCRIPTION, TRANSACTIONUPDATE, and TRANSACTIONQUERY. Authenticated with a Webservices API alias (username) and password scoped to a site reference.

- **Human URL:** [https://help.trustpayments.com/hc/en-us/sections/360005821218-Webservices-API](https://help.trustpayments.com/hc/en-us/sections/360005821218-Webservices-API)
- **Base URL:** `https://webservices.securetrading.net/json/`

#### Properties

- [Documentation](https://help.trustpayments.com/hc/en-us/sections/360005821218-Webservices-API)
- [API Reference](https://help.trustpayments.com/hc/en-us/articles/11569681677713-Webservices-API-Guide-for-POS-developers)

### Trust Payments Payouts API

Payout / disbursement capability exposed through the Webservices API on the TRU Connect gateway, using the same STPP JSON interface and alias/password + site reference authentication.

- **Human URL:** [https://help.trustpayments.com/hc/en-us/articles/4402771924497-Payouts-with-Webservices-API](https://help.trustpayments.com/hc/en-us/articles/4402771924497-Payouts-with-Webservices-API)
- **Base URL:** `https://webservices.securetrading.net/json/`

#### Properties

- [Documentation](https://help.trustpayments.com/hc/en-us/articles/4402771924497-Payouts-with-Webservices-API)

### Trust Payments JavaScript Library (ST.js)

Client-side JavaScript Library for embedding hosted, PCI-reduced card input fields and tokenising payments in the browser. Requests are authorised with a server-generated JSON Web Token (JWT). Distributed via the SecureTrading GitHub organisation with a matching iOS/Swift SDK.

- **Human URL:** [https://help.trustpayments.com/hc/en-us](https://help.trustpayments.com/hc/en-us)

#### Properties

- [Documentation](https://help.trustpayments.com/hc/en-us)
- [Source Code](https://github.com/SecureTrading)

## Common Properties

- [Website](https://www.trustpayments.com/)
- [Documentation](https://help.trustpayments.com/hc/en-us)
- [API Reference](https://help.trustpayments.com/hc/en-us/sections/360005821218-Webservices-API)
- [GitHub Organization](https://github.com/SecureTrading)
- [Status Page](https://status.trustpayments.com/)
- [Pricing](https://www.trustpayments.com/pricing/)
- [Blog](https://www.trustpayments.com/blog/)
- [Help Centre](https://help.trustpayments.com/hc/en-us)
- [Login (MyST)](https://myst.trustpayments.com/)
- [Terms of Use](https://www.trustpayments.com/terms-of-use/)
- [Privacy Policy](https://www.trustpayments.com/privacy-policy/)

## API Posture

Trust Payments does not publish a downloadable OpenAPI/Swagger definition or a dedicated developer subdomain. The API is documented as help-centre reference articles plus official SDKs (Python, PHP, ReactJS, Swift) on the [SecureTrading](https://github.com/SecureTrading) GitHub organisation. Production Webservices access is gated behind PCI certification, account approval, and credential exchange. No OpenAPI specs were harvested because none are published.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
