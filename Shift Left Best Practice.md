# Shift Left, Shift Right and Shift Everywhere

## Overview
**Shift Left testing** is absolutely a best practice in DevOps, it is one of the foundational pillars of modern software engineering and a holistic approach called Shift Everything, where security, performance, and compliance are also integrated into the very beginning of the lifecycle
Prior to adopting agile practices like Shift Left development, testing has been a **bottleneck** that seriously impedes on-time project delivery. Eliminating this bottleneck is one of the key benefits of Shift Left in DevOps.

---
### Shift Left vs. Shift Right: A Quick Comparison

| Feature | Shift Left (The Shield) | Shift Right (The Sensor) |
| :--- | :--- | :--- |
| **When?** | Before Release (Development) | After Release (Production) |
| **Primary Goal** | Stop bugs from reaching users. | Ensure stability and learn from users. |
| **Key Tools** | Unit tests, Code reviews, SAST. | Feature flags, Monitoring, A/B testing. |
| **Philosophy** | "Build it right the first time." | "Keep it running and make it better." |

---
## What does Shift Left mean in software development?

Shift Left is a practice intended to find and prevent defects early in the software development process. The idea is to improve quality by moving tasks to the left as early in the lifecycle as possible. Shift Left testing means testing earlier in the software development process.

The easiest way to explain the meaning of Shift-Left software testing is to think of the development cycle as a line running from left to right.

* **The Old Model:** Testing only came into play on the far right of the line.
* **The New Model:** Recognizing the bottleneck, we now move the initiation of testing as far to the left as possible.

---

## Why Shift Left is considered a "Best Practice"?

In the traditional software development model, requirements are kept on the left side of the plan, and the delivery and testing requirements on the right. The problem is that these practices can’t handle changing expectations and requirements, resulting in negative outcomes for the business such as:

* **Increased costs**
* **Increased time to market**
* **Unexpected errors**


The goal of DevOps is to increase velocity without sacrificing quality. Shift Left achieves this through:

* **Cost Efficiency: As highlighted in your previous text, fixing a bug in the requirements phase is roughly 100x cheaper than fixing it in production.**

* **Faster Feedback Loops: Developers find out if their code works in minutes (via automated CI/CD pipelines) rather than weeks (via a manual QA department).**

* **Improved Security (DevSecOps): By shifting security left, you catch vulnerabilities like hardcoded secrets or insecure dependencies before they ever reach a server.**

* **Reduced "Technical Debt": It prevents teams from building massive features on top of buggy foundations, which leads to cleaner, more maintainable codebases.**


---

## 6 Benefits of Shift Left Testing

There are several benefits that can be obtained by adopting a Shift Left strategy in DevOps. Here are some of the most important:

### 1. Reduced Costs
Cost alone is a very strong benefit of the Shift Left approach. Estimates indicate that **over half of all software defects** could be identified during the requirements phase, with less than 10% emerging during the development phase. 

> **The Cost Gap:**
> * A defect removed after the product has gone into production costs around **100 times more** than one identified during the requirements phase.
> * Research from the **Ponemon Institute (2017)** found that vulnerabilities detected early cost around **$80** on average, whereas they cost around **$7,600** to fix if detected after moving into production.

### 2. Enhanced Testing Automation
Shifting left gives a greater ability to automate testing. Test automation provides critical benefits:
* Much fewer human errors.
* Increased test coverage (multiple tests conducted simultaneously).
* Ability for testers to focus on more interesting and fulfilling tasks.
* Fewer production issues.

### 3. Increased Software Delivery Speed
Earlier means faster. When you find defects earlier in the production cycle, you can also fix them a lot faster. As a result:
* The time between releases can reduce significantly.
* The quality of software improves.

### 4. Improved Product Quality
The Shift Left approach emphasizes the need for developers to concentrate on quality from their **earliest stage** of a software build, rather than waiting for errors and bugs to be found late in the SDLC.

### 5. Increased Client Satisfaction
Faster delivery of software with fewer defects is a major benefit. If nothing else convinces you that this is a good move, the smiles on the faces of your business partners should be all you need.

* **Case Study:** Learn from the choices **Humana** made when selecting a modern mainframe development environment for editing and debugging code to improve their velocity, quality, and efficiency.

### 6. Improved Team Collaboration
Shifting left enables product teams to perform daily tasks like:
* Testing
* Providing feedback
* Reviewing changes and progress

---
# How to Implement Shift Left Testing

Transitioning to a Shift Left model requires more than just a change in tools; it requires a strategic overhaul of the development lifecycle. Below are the core strategies for successful implementation.

---

## 🛠 Key Shift Left Strategies

### 1. Demand Planning
Test analysts engage with business and operational stakeholders to provide a forward-looking view of demand. This allows the team to plan and finalize the following ahead of time:
* **Budgeting:** Financial allocation for quality tools and infrastructure.
* **Resourcing:** Ensuring the right personnel are available.
* **Test Strategies:** Mapping out the path to quality before a single line of code is written.

> **Note:** Demand planning is the foundation of the Shift Left approach and serves as the starting point for all subsequent activities in the test lifecycle.

### 2. Static Testing
Carried out in the earliest cycles of the project, static testing involves the validation of **requirements and design**. 
* **Goal:** To find defects that would be expensive to remove in later phases.
* **Action:** Use specialized checklists to verify requirements. All identified issues should be logged into a defect management tool immediately.

### 3. Unified Test Strategy
This is a high-level, end-to-end strategy covering everything from **Unit Testing** to **User Acceptance Testing (UAT)**, **Operational Readiness Testing (ORT)**, and **Post-deployment Testing**.
* It defines clear responsibilities across all phases of quality control.
* It allows teams to analyze dependencies on environments, stubs, automation, and test data early on.

### 4. Risk-Based Analysis
This analysis determines the **impact and likelihood of failure** for every test scenario, including functional, non-functional, and regression types.
* **Priority:** Establish test case priority based on the analysis.
* **Collaboration:** Discuss the "impact of failure" with business analysts and the "likelihood of failure" with the development team.

---

## ⚠️ Challenges in Adopting Shift Left Testing

While the benefits are clear, several challenges can impede the adoption of Shift Left testing:

| Challenge | Description |
| :--- | :--- |
| **Insufficient Leadership** | Leaders must incentivize quality. A strict focus on launch dates often leaves no room for early-stage testing. |
| **Process Inertia** | Teams often rely on familiar, outdated tools. Cultural resistance can make it difficult to change established workflows. |
| **Limited Resources** | Shift Left can be perceived as an "extra" workload. Without proper support and staffing, teams may struggle to keep up. |
| **Late Tester Engagement** | Teams often make the mistake of delaying tester involvement, missing out on their most valuable contributions during the design phase. |
| **Unaligned Scope** | If testing protocols do not evolve alongside changes in software usage scenarios, the testing becomes irrelevant. |

---

> **Pro-Tip for GitHub:** When implementing these strategies, ensure your CI/CD pipeline documentation reflects who owns which part of the "Unified Test Strategy."


---

## Shift Left vs. Shift Right in DevOps

A Shift Left testing approach may not always be able to deliver optimal performance and functioning in a real-world environment. 
In such situations, a **Shift Right** testing strategy may help to:

* Enhance customer experience.
* Provide scope for implementation of test automation.
* Ensure better test coverage.


# Shift Right in Software Development

## What is Shift Right?
**Shift Right testing** is initiated from the right—specifically, **post-production**. In this practice, you test a completely built and functioning application to ensure it meets performance and usability standards in a live environment. 

By gathering reviews and feedback from targeted users, teams can further enhance the quality of the software based on actual usage rather than theoretical models.


# Shift Right acknowledges that the most important "test environment" is production. It focuses on:

## Testing in Production: Using techniques like Canary Releases (rolling out a feature to 5% of users first) to ensure nothing breaks before a full launch.

**Observability: Using tools like Datadog or Grafana to watch how the system behaves under real load.

Chaos Engineering: Purposely breaking parts of your production system (like shutting down a server) to ensure the system stays online for users.

User Feedback: Analyzing how real people use the product to decide what to build next.

### Key Characteristics
An important characteristic of the Shift Right approach is a willingness to:
* **Validate a hypothesis** by trying out new solutions in a real-world setting.
* **Collaborate with customers** to determine what is working (instead of working from assumptions).
* **Utilize continuous feedback** from users to help respond better to software failures.

---

## 6 Benefits of Shift Right Testing

Adopting Shift Right testing in your development processes provides significant advantages for the stability and evolution of your product:

### 1. Real-World Feedback from Users
Testing in production allows you to see how software performs in the real world when handled by **actual users in actual scenarios**. While you can try to replicate such environments in earlier testing phases, real-world usage often turns up unexpected issues that synthetic environments cannot trigger.

### 2. Continuous Monitoring
The DevOps culture of **continuous delivery** requires continuous testing. Shift Right testing and monitoring provide the essential feedback loop needed to make frequent releases with absolute confidence.

### 3. Faster Resolution of Production Issues
With Shift Right testing, you identify issues faster, allowing you to address them with speed. Efficient issue resolution ensures:
* Users suffer **less downtime**.
* Releases are significantly **more reliable**.

### 4. Better User Experience
When users are engaged with your team, they benefit from fast, responsive issue resolution and fewer long-term bugs. Eliminating bottlenecks and UI issues through continuous improvement leads to **higher user satisfaction**.

### 5. Prevent Major Defects
This approach allows you to identify performance issues, functional glitches, and UX problems early in the release cycle. By doing so, you can respond quickly **before these problems bloom into major setbacks**.

### 6. Eliminate Unpredictable Outcomes
Shift Right testing puts the team in a **proactive position**. Continuous monitoring dramatically lowers the possibility of unpleasant surprises or catastrophic failures after a deployment.

---

> **The Big Picture:** While Shift Left focuses on quality through prevention, **Shift Right** ensures excellence through resilience and real-world validation.


---
### The Perfect Balance: Shift Everywhere
Excellence in DevOps isn't choosing between Left or Right; it’s about a Continuous Feedback Loop.

* Shift Left saves us money by catching bugs early.
* Shift Right saves our reputation by ensuring our systems are resilient and our users are happy in the real world.
