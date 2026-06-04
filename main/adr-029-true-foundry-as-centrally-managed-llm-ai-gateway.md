---
status: "proposed"
date: 2026-06-04
decision-makers: Amulya Bondada
---

# ADR-029: True Foundry as centrally managed LLM/AI Gateway

## Context and Problem Statement

TrueFoundry AI Gateway is an enterprise AI infrastructure platform with comprehensive gateway capabilities, strong compliance certifications, and production-proven scale. It offers token-level observability and intelligent cost optimization.
There is a need for a centrally managed LLM gateway in Bayer, the current myGenAssist is not well supported for individual LLM deployments. With very little control on guardrails and protection measures, we seek an enterprise platform which can support growing Bayer AI needs.

## Decision Drivers

1. Establish centrally managed LLM Gateway as scalable & compliant entrypoint into LLM deployments across cloud vendors. Solution will be deployed on Bayer AWS Cloud and owned by AIIA platform.
2. Reuse existing LLM subscriptions from myGenAssist, keeping same principles for authentication and access management, cost control and security protection.
3. Offer guidance to use LLM Gateway for convenience, security, lowest cost and added value in everyday use and product development. Keep option of dedicated SmartCloud LLM subscriptions if needed, highlighting requirements and potential risks.
4. Replace LLM routing in myGenAssist backend with managed solution (currently based on open source LiteLLM) .

## Decision Outcome

**Status:** Review

**AC Recommendation:** 1.Establish True Foundry as the centrally managed LLM Gateway as scalable & compliant entrypoint into LLM deployments across cloud vendors

### Consequences

* Platform impacted: {"Enterprise All"}
* Cost estimate: _Not set_
* Technology stack: True Foundry, LLM Gateway, OpenAI API,

## Attachments

| File | Original name | Type | Size (bytes) | Uploaded by | Uploaded at | URL |
| --- | --- | --- | ---: | --- | --- | --- |
| 1780565310847-TrueFoundry LLM Gateway â Decision Record.pptx | TrueFoundry LLM Gateway â Decision Record.pptx | application/vnd.openxmlformats-officedocument.presentationml.presentation | 4204871 | Gopinath Rengasamy | 2026-06-04 | [TrueFoundry LLM Gateway â Decision Record.pptx](https://eadectestblob.blob.core.windows.net/smartea/1780565310847-TrueFoundry%20LLM%20Gateway%20%C3%A2%C2%80%C2%93%20Decision%20Record.pptx) |


## Record Metadata

| Field | Value |
| --- | --- |
| Decision ID | ADR-029 |
| Platform | Enterprise All |
| Decision type | Strategic Demand |
| Decision phase | Review |
| Proposed date | 2026-06-03 |
| Finalized date | 2026-06-17 |
| Cost estimate | _Not set_ |
| Platform impacted | {"Enterprise All"} |
| Technology capability | AI and ML |
| Technology stack | True Foundry, LLM Gateway, OpenAI API, |
| BEAT reference | _Not set_ |
| AC recommendation | 1.Establish True Foundry as the centrally managed LLM Gateway as scalable & compliant entrypoint into LLM deployments across cloud vendors |
| Admin reviewed | Yes |
| AI session ID | _Not set_ |
| Created by | 9b1e5da1-a265-4e3a-88be-f246962e477a |
| Created at | 2026-06-04 |
| Updated at | 2026-06-04 |
| Attachment IDs | {"120474a0-7866-4f31-885e-fe3772e8dee7"} |
