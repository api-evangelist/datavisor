# DataVisor

DataVisor is a Mountain View, California fraud and risk platform company founded in 2013 that applies unsupervised machine learning, rules, device intelligence and link analysis to detect fraud and financial crime in real time for banks, credit unions, fintechs, digital payments, life insurance and digital enterprises.

The detection engine is consumed through APIs: customers stream user events to a DataVisor integration endpoint over real-time synchronous HTTPS REST (TLS 1.2 minimum), or through batch and cloud-bucket pipes, and receive detection results, risk scores and reason codes back. Named modules include the Fraud and Risk Platform, the dEdge device intelligence SDK and WebAPI, dOps, dVecto, the UML Modeling Studio and the Vera conversational AI agent.

**API documentation is not public.** The API references landing page is public, but the API guide is behind a download form, endpoint detail is held by each customer's technical account manager, and the console at `admin.datavisor.com` refuses anonymous requests. A full contract-discovery sweep found no OpenAPI, Swagger, GraphQL, AsyncAPI, MCP or A2A surface on any DataVisor host — the probe record is in `well-known/datavisor-well-known.yml`. Deployments are per customer on dedicated cloud machines, so there is no single public base URL and none is asserted.

- Website: https://www.datavisor.com/
- API references: https://www.datavisor.com/datavisor-api-guide
- Integration guide: https://www.datavisor.com/integrations/datavisor-integration-guide-for-comprehensive-fraud-solution
- Support: https://datavisor.zendesk.com/hc/en-us
- Secondary-market listing (harvest source): https://forgeglobal.com/datavisor_stock/
