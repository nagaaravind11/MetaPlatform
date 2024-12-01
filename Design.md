Design a next-generation data catalog that addresses the following challenges:

1. Background Task Management
2. Authentication and Authorization
3. Need for multiple Stores, and consistency between them — think about interfaces to consume metadata
4. Consider entities and relationships in the data model
5. Audits
6. Tenancy support OOTB
7. CNCF nature day 0 - cloud agnostic yet multi-cloud ready
8. Distributed Caching — case for it or not?
9. Modes of ingestion — batch/stream/both?
10. Notifications
11. Scalability and Extensibility - to ***activate*** the metadata layer in the true sense of the word
12. Scope for innovation with disruptive technologies, like Generative AI, Analytical workloads and reporting, metadata contextualised data querying
13. Support pluggable datastores
14. Deployment models and capacities contingent cost

While you design the solution, we would like you to also consider the following aspects : 

1. **Existing Metadata Engines**
    - Evaluate existing metadata engines (Amundsen, Open Metadata, Datahub, Apache Atlas) along with their limitations and identify areas for improvement.
2. **Cost-Efficiency**
    - Consider cost optimization when designing and deploying the solution in the cloud. Propose strategies to minimize expenses.
3. **Deployment and Observability**
    - Design a cloud-based deployment model for the data catalog, including monitoring and observability features to ensure system health and performance.
4. **Enterprise readiness**
    - This will be used by enterprises of the world, in programmatic ways beyond just Atlan UI and tight/loose integrations. In addition, the scale can be upto billions of metadata assets


## Guidelines

- Document your proposed system design and architecture at both high and low levels.
- Mention any architectural trade-offs and considerations made.
- Provide technical justifications for your design choices.
- Take into account the cost of deployment and provide cost-saving measures where applicable.
- Consider the future scalability and extensibility of the solution.
- Explore and evaluate existing metadata engines to identify their limitations and propose improvements.
- Explain which technologies, frameworks, or tools you would use and justify your choices.

## Your submission should include:

1. A detailed design document outlining your proposed system architecture, components, and interaction flows.
2. An explanation of the challenges addressed and how your solution mitigates them.
3. An E-R of the metadata model, and how you’d want to persist it across various stores
4. High-level design on interfaces you will want to expose

We understand this might be a very comprehensive challenge but believe we must understand each other better as we advance these discussions.
