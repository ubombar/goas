# What is GOAS?

GOAS (Goal-Oriented Agent System) is a control plane for building and operating goal-driven agent systems. It enables users to define high-level objectives, which are translated into structured key results (OKRs), and executed through dynamically assigned agent roles.

Instead of relying on predefined workflows or static pipelines, GOAS treats execution as a function of the objective. Given a goal, the system determines what roles are required, how they should interact, and how progress should be measured. This allows agent systems to adapt their structure and behavior at runtime.

At its core, GOAS separates planning from execution:

* The **control plane** (GOAS) is responsible for interpreting objectives, generating OKRs, assigning roles, tracking progress, and optimizing execution.
* The **data plane** (agents) consists of isolated runtimes that perform concrete actions such as retrieving data, analyzing content, or interacting with external systems.

GOAS continuously evaluates progress against defined key results and adjusts the system accordingly. This may involve reassigning roles, introducing new roles, retrying failed steps, or refining the execution strategy. The result is a feedback-driven system that focuses on achieving outcomes rather than executing fixed tasks.

The system is designed to be observable and interactive. Users can inspect objectives, OKRs, roles, and task states in real time, and intervene when necessary to guide or correct execution.

In essence, GOAS turns agent orchestration into a goal-driven process: you define what success looks like, and the system determines how to get there.
