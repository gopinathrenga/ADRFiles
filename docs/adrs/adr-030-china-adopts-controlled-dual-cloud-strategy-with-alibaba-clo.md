# China adopts controlled dual-cloud strategy, with Alibaba Cloud and Amazon Web Services
-   Status: proposed
-   Deciders: Amulya Bondada
-   Date: 2026-06-03

## Platform Name
CH Product Experience

## Demand Type
Strategic Demand

## Description
To meet China's regulatory requirements and align with the China digital strategy (2030), there is an evaluation done to assess the current state cloud situation of Bayer China.
Ali cloud, Azure and AWS were evaluated on the primary requirements towards collaboration with Chinese hospitals, physicians, and patients, aligning with China's digital strategy across PH, CH and CS divisons.
A decision has to be taken on what cloud providers would be most suitable based on the business, Geopolitical & Cost Advantage

## Objectives
4 Business Scenarios are presented, they include
1. Run as-is without Alicloud
2.Introduction of Alicloud basic covering the essentials, running AWS and Azure in the current state
3. Introducing Alicloud connect, with AWS running and Azure Shutdown
4. Introducing Alicloud connect and running with AWS and Azure as-is

Option 3: Is the Approach that is being considered for further evaluation and the outcomes are

China adopts a controlled dual-cloud strategy, with Alibaba Cloud and Amazon Web Services China as the primary strategic cloud platforms. This deliberate approach ensures regulatory compliance, cost discipline, architectural consistency, and operational simplicity across all China operations. Unlike traditional multi-cloud strategies that prioritize optionality, this framework is intentionally focused and constrained.

## Decision
Review

## Recommendations
1. Approved Adoption of controlled dual-cloud strategy, with Alibaba Cloud and Amazon Web Services China
2. All new applications must be designed and deployed on Alibaba Cloud or Amazon Web Services China by default
3. New deployments on Azure China are not allowed without explicit exception approval.
4. Current applications running on Azure China will continue to operate to ensure business stability
5. Azure China is considered a non-strategic but tolerated platform for existing workloads only.
6. Migration from Azure China occurs only when triggered by application lifecycle events: business-driven upgrades, major technical refreshes, or platform End-of-Life. Migrations must be value-based and lifecycle-aligned.
7. Azure China may be used only under exceptional circumstances with highly specific business requirements or critical technical constraints. All exceptions require case-by-case architectural assessment and explicit governance approval

## Council Member
Amulya Bondada

## Platform Impacted
- {"CH Data Assets
- Analytics & AI"}

## Attachments
- [China Cloud Strategy 5.0 (1).pptx](https://eadectestblob.blob.core.windows.net/smartea/1780582984957-China%20Cloud%20Strategy%205.0%20(1).pptx) (application/vnd.openxmlformats-officedocument.presentationml.presentation, Gopinath Rengasamy)
