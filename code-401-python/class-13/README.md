# Day 13
## Serverless

### What is serverless?

Serverless is a cloud computing application development and execution model that enables developers to build and run application code without provisioning or managing servers or backend infrastructure.

Also important: With serverless, developers never pay for idle capacity. The cloud provider spins up and provisions the required computing resources on demand when the code executes, and spins them back down again—called ‘scaling to zero’—when execution stops. The billing starts when execution starts, and ends when execution stops; typically, pricing is based on execution time and resources required.

### Serverless does not mean 'no servers'

The name notwithstanding, there are most definitely servers in serverless computing. 'Serverless' describes the developer’s experience with those servers—they are are invisible to the developer, who doesn't see them, manage them, or interact with them in any way.

Today every leading cloud service provider offers a serverless platform including Amazon Web Services (AWS Lambda), Microsoft Azure (Azure Functions), Google Cloud (Google Cloud Functions) and IBM Cloud (IBM Cloud Code Engine). Together serverless computing, microservices and containers form a triumvirate of technologies typically considered to be at the core of cloud-native application development.

### Pros and cons of serverless

#### Pros

Given all of the preceding, it should be no surprise that serverless computing offers a number of technical and business benefits to individual developers and enterprise development teams.

1- Improved developer productivity: As noted above, serverless enables development teams to focus on writing code, not managing infrastructure. It gives developers much more time to innovate and optimize their front-end application functionality and business logic.

2- Pay for execution only: The meter starts when the request is made, and ends when execution finishes. Compare this to the infrastructure as a service (IaaS) compute model, where customers pay for the physical servers, virtual machines (VMs) and other resources required to run applications, from the time they provision those resources until the time they explicitly decommission them.

3- Develop in any language: Serverless is a polyglot environment, enabling developers to code in any language or framework—Java, Python, JavaScript, node.js—with which they're comfortable.

4- Streamlined development/DevOps cycles. Serverless simplifies deployment and, in a larger sense, simplifies DevOps because developers don't spend time defining infrastructure required to integrate, test, deliver and deploy code builds into production.

5- Cost-effective performance. For certain workloads—embarrassingly parallel processing, stream processing, certain data processing tasks—serverless computing can be both faster and more cost-effective than other forms of compute.

6- Usage visibility. Serverless platforms provide near-total visibility into system and user times and can aggregate usage information systematically.

#### Cons

With so much to like about serverless, organizations are using it for a wide variety of applications (see Figure 2 below). But there are drawbacks—some of which are related to specific applications, and others which are universal.

1- Unacceptable latency for certain applications: Because serverless architectures forgo ongoing processes in favor of scaling up and down to zero, they also sometimes need to start up from zero to serve a new request. For many applications the resultant delay would not be detrimental or even noticeable to users. But for others—say, a financial trading application—this cold-start latency might be unacceptable.

2- Higher costs for stable or predictable workloads: Because serverless scales up and down on demand in response to workload, it offers significant cost savings for spiky workloads. But it does not offer the same savings for workloads characterized by predictable, steady or long-running processes; in these cases, a traditional server environment might be simpler and more cost-effective.

3- Monitoring and debugging issues: These operational tasks are challenging in any distributed system, but serverless architecture (or microservices architecture, or a combination of the two) only exacerbates the complexity. For example, teams may find it difficult or impossible to monitor or debug serverless functions using existing tools or processes.

4- Vendor lock-in: As noted, one of the biggest advantages of serverless is that the cloud provider manages all the computing resources. While this frees up considerable time for developers to focus on writing and improving their code, it also means that migrating code to a new cloud provider could prove challenging. Many cloud provider’s serverless platforms are designed to provide an ecosystem of managed cloud services and are not portable like virtual machines (VMs) or Docker containers. Application code that triggers several services offered by one cloud provider’s serverless platform might have to be partially or completely rewritten to get get the same results in another provider’s platform.

> ## Referances

1- https://www.ibm.com/cloud/learn/serverless
