# Cross Functional Platform Integrations & Ecosystem Development

## Problem
KARE decided to make a strategic pivot to expand into adjacent senior care segments by introducing three new platforms:
* **NASTi** - A scheduling platform and operations tool for senior care operators
* **Know** - A professional social network for caregivers and nurses
* **Seen** - An eCommerce storefront selling branded scrubwear

The original marketplace was not designed to support a multi-product ecosystem. Each platform had separate identity, permission, and onboarding systems. This created two major blockers:
* Customer acquisition friction due to duplicated onboarding and broken cross-product flows
* Elevated support volume caused by inconsistent permissions, account mismatches, and manual intervention
* Inability to purchase scrubwear directly through the partner platforms

The risk was clear - launching new products added increased complexity instead of compounding value.

## Solution
I led the product integration strategy to remove architectural blockers that prevented scale in both acquisition and support.

This included:
* Partnering with other team PMs, engineering leads, and executives across three additional product teams to align on shared outcomes and success criteria.
* Facilitated weekly cross-platform “sync-and-solve” sessions to unblock architectural and experience challenges 
* Conducted gap analysis across authentication, user models, and permissions to define a scalable integration approach
* Collaborating with engineers to replace the legacy store with Shopify APIs and embedded experiences while preserving usability and launch timelines


### Know ↔ Marketplace
* Implemented single sign-on and federated user profiles to allow caregivers to move seamlessly between products
* Exposed marketplace functionality via APIs so caregivers could access Know’s AI-powered resume tools directly within the marketplace
* Designed deep-linking flows that allowed advanced editing in Know while preserving marketplace credentials
* Enabled in-app acquisition via contextual ad placements that supported instant account creation

### NASTi ↔ Marketplace

* Synced core workflows including shift posting, user management, and role-based permissions
* Partnered with engineers to design a federated identity model that allowed users to transition between platforms while enforcing authorization boundaries
* Ensured users retained correct access levels without introducing security gaps or duplicated configuration


## Results and Impact

* Unblocked customer acquisition by removing cross-platform onboarding friction, enabling Know’s successful launch
* More than doubled daily caregiver signups compared to baseline marketplace acquisition rates
* Enabled NASTi’s pilot launch with 60+ senior care buildings, validating demand without increasing support burden
* Reduced architecture-driven support tickets by eliminating account mismatches and permission inconsistencies
* Established a repeatable integration pattern that lowered risk for future ecosystem partnerships
* Launched the Seen eCommerce experience on time, with orders placed day one directly within the marketplace application

