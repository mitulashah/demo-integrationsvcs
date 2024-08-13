# Azure Integration Services - DevOps Demos

## API Management - APIOps

A demonstration of the [APIOps DevOps](https://azure.github.io/apiops/) approach for Azure API Management:

![API Ops](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/devops/media/automated-api-deployments-architecture-diagram.png)

### Basic Concepts

- APIOps applies the concepts of GitOps and DevOps to API deployment. By using practices from these two methodologies, APIOps can enable everyone involved in the lifecycle of API design, development, and deployment with self-service and automated tools to ensure the quality of the specifications and APIs that they’re building.

- APIOps places the Azure API Management infrastructure under version control to achieve these goals. Rather than making changes directly in API Management, most operations happen through code changes that can be reviewed and audited. This approach supports the security principle of least-privilege access.

- APIOps not only enforces policies within API Management, but also helps support security by providing feedback for proposed policy changes. Early feedback is more convenient for developers and reduces risks and costs. Also, the earlier in the pipeline that you can identify deviations from your standards, the faster you can resolve them.

- Also, the more APIs that you build and deploy by following this approach, the greater the consistency between APIs. With greater consistency, it’s less likely that the service can’t or won’t be consumed because of low quality.
