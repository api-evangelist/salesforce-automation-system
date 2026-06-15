# Salesforce Automation System (salesforce-automation-system)

Salesforce Automation System refers to the collection of APIs and tools within Salesforce for automating business processes, including Flow Builder, approval processes, Process Builder, and Workflow Rules. These capabilities enable organizations to automate CRM, sales, marketing, and customer service workflows programmatically via the Salesforce REST API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/salesforce-automation-system/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/salesforce-automation-system/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Approval Process
- Automation
- CRM
- Flow
- Process Builder
- Salesforce
- Workflow

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Salesforce Flow Automation API

REST API for querying Salesforce Flow definitions via the Tooling API, invoking autolaunched flows as REST actions, and managing approval process submissions and decisions.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable.htm](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable.htm)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v59.0`

#### Tags

- Approval Process
- Automation
- CRM
- Flow
- Salesforce
- Workflow

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable.htm)
- [OpenAPI](openapi/salesforce-automation-flow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-automation-flow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-automation-flow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/salesforce-flow-definition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/salesforce-approval-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/salesforce-automation-system-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/salesforce-automation-system-rules.yml)
- [Capabilities](capabilities/process-automation.yaml)
- [Vocabulary](vocabulary/salesforce-automation-system-vocabulary.yml)

### Salesforce Flow Builder

Visual automation tool for building screen flows, autolaunched flows, record-triggered flows, and scheduled flows without code.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.flow.meta/flow/flow_intro.htm](https://developer.salesforce.com/docs/atlas.en-us.flow.meta/flow/flow_intro.htm)

#### Tags

- Automation
- Flow
- No-Code
- Salesforce

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.flow.meta/flow/flow_intro.htm)
- [Getting Started](https://trailhead.salesforce.com/content/learn/trails/automate_business_processes)
- [Postman Collection](collections/salesforce-automation-flow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-automation-flow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Approval Processes

Multi-step approval automation for routing records through review chains with configurable criteria, approvers, and post-approval actions.

- **Human URL:** [https://help.salesforce.com/s/articleView?id=sf.approvals_landing_page.htm](https://help.salesforce.com/s/articleView?id=sf.approvals_landing_page.htm)

#### Tags

- Approval
- Automation
- CRM
- Salesforce

#### Properties

- [Documentation](https://help.salesforce.com/s/articleView?id=sf.approvals_landing_page.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_process_approvals.htm)
- [Postman Collection](collections/salesforce-automation-flow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-automation-flow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Developer  Portal](https://developer.salesforce.com/)
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/)
- [Trailhead](https://trailhead.salesforce.com/content/learn/trails/automate_business_processes)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm)
- [Blog](https://developer.salesforce.com/blogs)
- [Status Page](https://status.salesforce.com/)
- [Support](https://help.salesforce.com/)
- [Terms of Service](https://www.salesforce.com/company/legal/agreements/)
- [Privacy Policy](https://www.salesforce.com/company/privacy/)
- [GitHub Organization](https://github.com/salesforce)
- [Community](https://trailhead.salesforce.com/trailblazer-community/topics/salesforcedeveloper)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
