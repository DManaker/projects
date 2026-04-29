# Cross Functional Platform Integrations and Ecosystem Development

## Situation
Leadership decided to pivot strategies and expand the company into new industry segments which included the addition of new platforms like NASTi, a scheduling tool, and Know, a social media platform, dedicated to caregivers and nurses in the senior care staffing space.

By creating an ecosystem, caregivers who used the marketplace could advance their careers, network, and find permanent employment opportunities via Know, and operators could have a third-party staffing marketplace integrated with their scheduling software. 

This presented many architectural challenges that involved connecting different platforms together to the core marketplace including shared interface experiences, single sign on, and federated user accounts.

## Solution
Cross-functional work was essential with other product managers, engineers, and leadership teams assigned to each platform to ensure that both business and experience goals were met. I led weekly sync-and-solve meetings, performed gap analysis, and prioritized documenting and structuring our APIs to allow for seamless transition across platforms.

With Know and KARE, we'd integrate user profiles through single sign on capabilities and link app features together. For example, our caregivers would be able to access Know's AI resume enhancement features through API in KARE Marketplace. If a user wanted to make additional edits, they'd be directed to the social network platform with their marketplace credentials to make further changes. In addition, we set up many in-app advertisement placements to allow for instant sign up through the marketplace app.

Between NASTi and KARE, the solution was to sync user experiences such as shift posting, user management, and permission management between the two platforms. To ensure users could navigate betweeen platforms, we had to work with our engineers to architect a federation that allowed users to transition from one platform to the other, but had the applications retain permission sets that could be transmissable across platforms so that users were not being able to access unauthorized features.

## Results and Impact
By working together on our platform integration, the NASTi team was able to get a pilot signup of >60 buildings. This ensured a good foundation for continued iteration and learning. It also helped drive shifts into our core marketplace platform resulting in modest revenue increases.

