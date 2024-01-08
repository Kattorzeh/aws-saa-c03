<h1>Global Theory</h1>
<h2>1. Cloud Computing</h2>
Cloud Computing need:

1) <b>On-Demand Self-Service:</b> Can provision capabilities as needed without requiring human interaction
2) <b>Broad Network Access:</b> Capabilites are available over the network and accessed through standard mechanisms (protocols and methods)
3) <b>Resource Polling:</b> There is a sense of location indepenence (no control/knowledge over the exact location of the resources) and Resources are pooled to serve multiple consumers (brings economies of scale)
4) <b>Rapid Elasticity:</b> Can Scale Up/Down automatically in response to syystem load (to the Customers, the capabilites available for provisioning often appear to be unlimited)
5) <b>Measured Service:</b> Resource usage can be monitored/controlled/reported and billed (pay for what you consume)

<h2>2. Types of Cloud</h2>

- <b>Public Cloud:</b> meet the 5 req, only use 1 Vendor and is available to the general public (AWS, Azure, GCP)
- <b>Multi  Cloud:</b> use more than 1 public Cloud (have Cloud vendors resilience and get best of each)
- <b>Private Cloud On-Premises:</b> mmet 5 req but is dedicated to you as a business (use on-premises real cloud)
- <b>Hybrid Cloud:</b> use both public and private working together as a single env.
- <b>Hybrid Environmet:</b> use public cloud with your on-premises infrastructure.

<h2>Cloud Service Models</h2>

- <b>Infrastructure Stack:</b> collections of things which any app that exists needs and they are stacked to each other (facilities-infrastructure-servers-virtualization-o/s-container-runtime env-data-app). There are parts that you manage and parts managed by the vendor.
- <b>On-Premises:</b> you need to manage all parts of the infrastructure stack (is complex but gives big flexibility)
- <b>DC Hosted:</b> placed your infra inside the DC (Vendor manages Facilities)
- <b>IaaS:</b> Vendor manages facilities->virtualization, you Consume o/s and you manage o/s->app (you pay for the time you use the VM)
- <b>PaaS:</b> Vendor manages facilities->container, you consume runtime and you manage runtime->app ("mainly used by developers who want their app to run without worrying about the underlying infra)
- <b>SaaS:</b> Vendor manages facilities->data, you Consume/mange app (netflix, dropbox, mail...)
