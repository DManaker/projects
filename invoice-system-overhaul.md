# Financial Infrastructure & Revenue Recovery System

## Problem
At KARE, the invoicing and payment infrastructure was a significant bottleneck to scaling, characterized by three critical failure points:
* Sending invoices and collecting payments were done through a third-party via snail mail resulting in antiquated payment methods.
* Due to the nature of our business and billing, we effectively fronted money and relied on payment second, leading to some delinquent payors being taken to court for non-payments and breach of contract, resulting in hundreds of thousands of legal fees.
* Our invoice system had a split source-of-truth, being shared between our marketplace app (KARE) and Quickbooks, leading to friction in business logic, damaging long-term customer retention rates.

## Solution
* Create an interface that supported a digital payment system through our company bank.
* Work cross functionally with the finance team to establish something called a "Credit Limit," proactively notifying internal and external users that were close to reaching their limit established by our finance team prior to onboarding reducing the risk of delinquent payments and court fees.
* Create a system where finance team members could go into our marketplace app on the staff portal and dictate business logic rules based on invoice lapses, like delaying the cancellation of open shifts or outright suspending a community who may have not been a repeat offender and was offered some grace period.
* Create an internal tool where the finance team could manage invoice changes bi-directionally and API could handle the update requests so that the Quickbooks and Marketplace apps were aligned.

## Impact & Results
* Allowed customers to have more streamlined payment systems, reducing late deliveries and delinquent payments.
* Helped our finance team be proactive in monitoring company activity and stopping risky partners from going past their allotted credit limits and risking failed payments and numerous court costs to reclaim payments.
* Maintain customer satisfaction with good partners that may deserve grace periods to due lapses in payment and prevent attrition.
* Allowed internal teams the flexibility of making changes without the need for IT support help and numerous database manipulation techniques to align source of truth systems.
