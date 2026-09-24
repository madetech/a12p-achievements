## Theme 7: Release & Deployment Automation

### Ship It Automatically
**Duties:** D6 · **KSBs:** K15, K17, S15

Implement release/deployment orchestration (using an API where relevant) as part of a continuous delivery or continuous deployment pipeline, enabling the team to ship a real change to users through it.

### Kill the Toil
**Duties:** D12 · **KSBs:** K13, S12

Identify a manual task that is repeated regularly and automate it (via scripting or an API). Quantify or clearly describe the time/effort saved, and weigh this against the cost of building the automation.

### Zero Downtime *(advanced)*
**Duties:** D6 · **KSBs:** K15, S15

Implement a deployment strategy (blue/green, canary, or rolling) that allows your team to release a real change without user-facing downtime. Show what would have happened under the old approach vs the new one.

### Pipeline, Your Way *(advanced)*
**Duties:** D5, D6 · **KSBs:** K15, K24, S15

Rebuild an existing deployment pipeline's capability using an alternate CI/CD tool or stack to the one your team normally uses. Compare the tradeoffs (SaaS vs bespoke vs enterprise tooling, ease of use, cost, lock-in) between the two.

### Ephemeral Test Environments *(advanced)*
**Duties:** D5, D6 · **KSBs:** K1, K15, S15

Automate the creation and teardown of a temporary test/preview environment, triggered automatically by opening a pull request and torn down automatically when it's closed or merged. Show a real PR triggering the environment and its automatic teardown.