# DataVisor

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

DataVisor is a Mountain View, California fraud and risk platform company founded in 2013 that applies unsupervised machine learning, rules, device intelligence and link analysis to detect fraud and financial crime in real time for banks, credit unions, fintechs, digital payments, life insurance and digital enterprises.

The detection engine is consumed through APIs: customers stream user events to a DataVisor integration endpoint over real-time synchronous HTTPS REST (TLS 1.2 minimum), or through batch and cloud-bucket pipes, and receive detection results, risk scores and reason codes back. Named modules include the Fraud and Risk Platform, the dEdge device intelligence SDK and WebAPI, dOps, dVecto, the UML Modeling Studio and the Vera conversational AI agent.

**API documentation is not public.** The API references landing page is public, but the API guide is behind a download form, endpoint detail is held by each customer's technical account manager, and the console at `admin.datavisor.com` refuses anonymous requests. A full contract-discovery sweep found no OpenAPI, Swagger, GraphQL, AsyncAPI, MCP or A2A surface on any DataVisor host — the probe record is in `well-known/datavisor-well-known.yml`. Deployments are per customer on dedicated cloud machines, so there is no single public base URL and none is asserted.

- Website: https://www.datavisor.com/
- API references: https://www.datavisor.com/datavisor-api-guide
- Integration guide: https://www.datavisor.com/integrations/datavisor-integration-guide-for-comprehensive-fraud-solution
- Support: https://datavisor.zendesk.com/hc/en-us
- Secondary-market listing (harvest source): https://forgeglobal.com/datavisor_stock/
