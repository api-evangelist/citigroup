# Citigroup (citigroup)
Citigroup (Citi) is a global, diversified money-center financial services holding company headquartered in New York City, serving consumers, corporations, governments, and institutions across roughly 90 countries. Citi exposes public API access through two distinct, voluntary developer surfaces: the retail **Citi Developer Hub** (developer.citi.com, launched 2016, now consolidated into the **Citi Partner Portal** at partner.citi.com) and the corporate **CitiConnect** program within Treasury and Trade Solutions (TTS).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/citigroup/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:

 - Banking, Financial Services, United States, Money Center Bank, Open Banking, Open Finance, Treasury and Trade Solutions, CitiConnect, Payments, FX, Corporate Banking, Fortune 100

## Timestamps

- **Created:** 2026-03-23
- **Modified:** 2026-07-23

## APIs

### Retail — Citi Developer Hub (partner.citi.com)

- **Citi Accounts and Transactions API** — authorized access to retail accounts, balances, and transaction histories. Tags: Accounts, Balances, Banking, Statements, Transactions.
- **Citi Money Movement API** — payment initiation (ACH, wire, book transfer) from Citi accounts. Tags: ACH, Money Movement, Payment Initiation, Payments, Wire Transfer.
- **Citi Authorize API** — OAuth 2.0 authorization-code and consent flows for third-party access. Tags: Authorization, Consent, OAuth, SCA.
- **Citi Customers API** — authorized customer profile access for onboarding and KYC. Tags: Customers, Identity, KYC, Profiles.
- **Citi Onboarding API** — digital account opening, document submission, and KYC origination. Tags: Account Opening, Customer Onboarding, KYC, Origination.
- **Citi Pay with Points API** — ThankYou points and rewards redemption at checkouts and partner apps. Tags: Loyalty, Pay with Points, Rewards.
- **Citi Utilities API** — FX rates, branch/ATM locators, and reference data. Tags: FX Rates, Locator, Reference Data, Utilities.

### Corporate — CitiConnect (Treasury and Trade Solutions)

- **CitiConnect API** — real-time payments, request-to-pay, direct debits, faster payments, and account-balance inquiry for enterprise ERP/TMS integration. 1B+ calls since 2017. Tags: CitiConnect, Corporate Banking, ERP Integration, TTS, Real-Time Payments.
- **CitiConnect WorldLink Payment Services API** — cross-border, multi-currency payments with FX enquiry and deal booking, 24x7. Tags: WorldLink, Cross-Border Payments, FX, CitiConnect, TTS.
- **CitiConnect FX (Real-Time FX) API** — real-time FX rate requests and contract booking from ERP/TMS. Tags: FX, Foreign Exchange, CitiConnect, TTS.
- **CitiConnect Statements and Reporting API** — statements, reporting, cut-off times, and proof of payment. Tags: Statements, Reporting, Proof of Payment, CitiConnect, TTS.

## Auth & Open-Finance Posture

- **Retail:** OAuth 2.0 authorization-code / customer-consent flows, sandbox-brokered.
- **Corporate (CitiConnect):** OAuth 2.0 with mutual TLS (mTLS).
- **Open finance:** US voluntary regime. Citi is a **co-owner of Akoya**, the FDX-aligned consumer-permissioned data-access network, its primary channel under CFPB Section 1033 norms.
- **Specs:** No public downloadable OpenAPI, Swagger, Postman, or SDK — documentation is HTML and partner-gated.

## Common Properties

- [Website](https://www.citigroup.com)
- [Developer Portal](https://developer.citi.com/)
- [Partner Portal](https://partner.citi.com/)
- [Documentation](https://partner.citi.com/developers)
- [API Catalog](https://sandbox.developerhub.citi.com/api-catalog-list)
- [CitiConnect](https://www.citigroup.com/global/insights/citiconnect-api-portal)
- [GitHub Organization](https://github.com/citi)
- [LinkedIn](https://www.linkedin.com/company/citigroup)
- [Blog / News](https://www.citigroup.com/global/news)
- [Investor Relations](https://www.citigroup.com/global/investors)
- [Terms of Service](https://online.citi.com/US/JRS/pands/detail.do?ID=Terms)
- [Privacy Policy](https://online.citi.com/US/JRS/pands/detail.do?ID=PrivacyTerms)
- [Support](https://online.citi.com/US/contactus.htm)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
