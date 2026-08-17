# Cloud Platform Recommendation Challenge
For each scenario:
- Identify the recommended cloud platform.
- Explain your recommendation in 3–5 sentences.
- Mention at least three services that the client could use.
## Client A – Startup Company
> Scenario: A startup company wants to launch a new mobile application. Their budget is limited, but they expect rapid growth within the next few years.

**Recommended Platform:** Amazon Web Services (AWS)

**Why:** 
While AWS offers unmatched perks for growing mobile apps, including a massive free tier, endless online troubleshooting support, and cost-effective serverless tools like AWS Lambda for unpredictable traffic, it comes with a steep learning curve and the constant risk of unexpected bill spikes. 

**Services that they could use:**
- CloudFront
- RDS 
- Lambda

## Client B – University
> Scenario: A university already uses:
> - Windows Server
> - Microsoft 365
> - Active Directory
> The university wants to migrate some services to the cloud.

**Recommended Platform:** Azure

**Why:** They already have Active Directory, Windows Server, and Microsoft 365 running. Migrating to Azure is like the path of least resistance. Their IT team probably already knows Microsoft stuff, and Azure AD integration is actually really smooth. But they're gonna get locked into Microsoft really hard and switching later is gonna be painful and expensive. So just make sure they should really want that before committing. 

**Services that they could use:**
- Virtual Machines
- Azure SQL Database
- Azure Active Directory

## Client C – AI Research Company
> Scenario: A research company develops Artificial Intelligence and Machine Learning applications that require high-performance computing.

**Recommended Platform:** Google Cloud Platform (GCP)

**Why:** Google literally invented machine learning research. Their AI tools aren't just good, they're kinda easy to use compared to competitors. BigQuery for analyzing massive datasets, Vertex AI for building models, and TensorFlow integration that just work. But GCP can be expensive for heavy compute workloads. Like, surprisingly expensive. If they're training massive networks 24/7, they might end up paying more than expected. Still worth it though because the tools are just better for this type of work. 

**Services that they could use:**
- CloudTPUs
- Vertex AI
- BigQuery

## Client D – Global E-Commerce Company
> Scenario: A multinational online shopping company serves customers around the world and requires highly available infrastructure with automatic scaling.

**Recommended Platform:** Amazon Web Services (AWS)

**Why:** For a global e-commerce company needing 99.9% uptime and auto-scaling. AWS is like the safest. They have data centers everywhere (like 30+ regions), their load balancing is battle-tested, and their auto-scaling just works. EC2, RDS, and CloudFront can handle massive traffic spikes. The real issue is that AWS is sooo good  that everyone uses it, so if AWS goes down (rarely), half the internet breaks. Some companies use multi-cloud now specifically to avoid putting all eggs in one basket. 

**Services that they could use:**
- EC2
- RDS
- CloudFront + S3

# Multi-Cloud Decision Matrix
| Business RequirementRecommended PlatformJustification |                    |                                                                                                                                                                                                                                                                      |
| ----------------------------------------------------- | ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Startup Company                                       | AWS                | Free tier with 12-month period, flexible pay-as-you-go pricing, largest ecosystem of tools and templates, excellent for rapid scaling                                                                                                                                |
| Enterprise Organization                               | Azure              | Strong enterprise support, seamless integration with Microsoft ecosystem, robust compliance and security features, dedicated account management                                                                                                                      |
| Microsoft Environment                                 | Azure              | Native integration with Office 365, Active Directory, Dynamics 365, and other Microsoft services, reduces operational complexity and licensing costs                                                                                                                 |
| AI / Machine Learning                                 | Google Cloud       | Industry-leading ML capabilities with Vertex AI, BigQuery for data analytics, TensorFlow support, superior data processing for ML workloads                                                                                                                          |
| Kubernetes Deployment                                 | Google Cloud (GKE) | Google created Kubernetes. GKE offers the most optimized and native Kubernetes experience with best-in-class management and auto-scaling                                                                                                                             |
| Global Web Application                                | AWS                | Largest global infrastructure with 30+ regions, CloudFront CDN for edge caching, excellent latency optimization worldwide, proven track record with global applications
