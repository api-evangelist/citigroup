# Citigroup (citigroup)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
