# Salesforce Automation System (salesforce-automation-system)
Salesforce automation APIs and tools for building Flow-based automation, approval processes, and workflow automation to automate CRM business processes programmatically.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/salesforce-automation-system/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Approval Process, Automation, CRM, Flow, Process Builder, Salesforce, Workflow

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-02

## APIs

### Salesforce Flow Automation API
REST API for invoking autolaunched flows, querying flow definitions via Tooling API, and managing approval process submissions.

**Human URL:** https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable.htm

#### Tags
- Approval Process, Automation, CRM, Flow, Salesforce, Workflow

#### Properties
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable.htm)
- [OpenAPI](openapi/salesforce-automation-flow-openapi.yml)
- [JSON Schema (Flow Definition)](json-schema/salesforce-flow-definition-schema.json)
- [JSON Schema (Approval Request)](json-schema/salesforce-approval-request-schema.json)
- [JSON-LD Context](json-ld/salesforce-automation-system-context.jsonld)
- [Spectral Rules](rules/salesforce-automation-system-rules.yml)
- [Capabilities](capabilities/process-automation.yaml)
- [Vocabulary](vocabulary/salesforce-automation-system-vocabulary.yml)

---

### Salesforce Flow Builder
Visual automation tool for building screen flows, record-triggered flows, and scheduled automations.

**Human URL:** https://developer.salesforce.com/docs/atlas.en-us.flow.meta/flow/flow_intro.htm

---

### Salesforce Approval Processes
Multi-step approval automation for routing records through configurable review chains.

**Human URL:** https://help.salesforce.com/s/articleView?id=sf.approvals_landing_page.htm

---

## Capabilities

### Shared Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/salesforce-automation-flow.yaml](capabilities/shared/salesforce-automation-flow.yaml) | Shared consumed definition for Salesforce Flow Automation API |

### Workflow Capabilities

| File | Description | APIs |
|------|-------------|------|
| [capabilities/process-automation.yaml](capabilities/process-automation.yaml) | Process automation (flows + approvals) | Salesforce Flow Automation API |

## Artifacts

| Artifact | Path |
|----------|------|
| OpenAPI Spec | [openapi/salesforce-automation-flow-openapi.yml](openapi/salesforce-automation-flow-openapi.yml) |
| JSON Schema (Flow) | [json-schema/salesforce-flow-definition-schema.json](json-schema/salesforce-flow-definition-schema.json) |
| JSON Schema (Approval) | [json-schema/salesforce-approval-request-schema.json](json-schema/salesforce-approval-request-schema.json) |
| JSON Structure | [json-structure/salesforce-automation-system-structure.json](json-structure/salesforce-automation-system-structure.json) |
| JSON-LD Context | [json-ld/salesforce-automation-system-context.jsonld](json-ld/salesforce-automation-system-context.jsonld) |
| Spectral Rules | [rules/salesforce-automation-system-rules.yml](rules/salesforce-automation-system-rules.yml) |
| Vocabulary | [vocabulary/salesforce-automation-system-vocabulary.yml](vocabulary/salesforce-automation-system-vocabulary.yml) |

## Examples

- [Invoke Flow](examples/salesforce-invoke-flow-example.json)
- [Submit Approval Request](examples/salesforce-submit-approval-example.json)

## Common Properties

- [Developer Portal](https://developer.salesforce.com/)
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/)
- [Trailhead](https://trailhead.salesforce.com/content/learn/trails/automate_business_processes)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm)
- [Status](https://status.salesforce.com/)
- [Support](https://help.salesforce.com/)
- [Terms of Service](https://www.salesforce.com/company/legal/agreements/)
- [Privacy Policy](https://www.salesforce.com/company/privacy/)
- [GitHub Organization](https://github.com/salesforce)
- [Community](https://trailhead.salesforce.com/trailblazer-community/topics/salesforcedeveloper)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
