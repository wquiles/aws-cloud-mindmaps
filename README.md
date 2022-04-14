# aws-cloud-mindmaps

#### What
This repo contains mindmaps that I have created about AWS based on public information.  Since all of the information is already in the public domain, feel free to use and share these mindmaps as you see fit.  

#### Why
This is how I learn.  Creating the mindmaps helps me learn, and helps me explain a topic to others.  I started using them with my customers and I got interrupted within a few min: "Will, can I please have that mindmap?".  After many of these encounters I realized I should make them available to others who might find them useful as well.

#### Software
I am using Xmind Desktop Pro V8 (now called Classic) to create these mindmaps.  These links below are read-only exports from Xmind Desktop Pro V8.  For those interested in downloading the free version, here is the [direct link](https://www.xmind.net/xmind8-pro/).

#### Contributions
Several colleagues I work with help me review content, suggest improvements, point out errors, typos, etc. - thanks much to Anna, Alvaro, Dario, Ron, and many others for your help.

#### Known issues
So far the only issue I know about is with the export from Xmind in terms of capitalizing.  For example, instead of "AWS Security Hub", the export shows as "Aws Security Hub".  We have contacted Xmind and they logged this bug, and hope that will be fixed in a future release.

#### Contact information
If you have suggestions, fixes, improvements, or ideas to make these better or create new ones, please contact me at my work email: quilesw@amazon.com.




# AWS Mindmaps

## AWS Security Hub
AWS Security Hub is a cloud security posture management service that performs security best practice checks, aggregates alerts, and enables automated remediation.  [(Link to mindmap version 4.12)](https://www.xmind.net/m/4t4uPC)


## Amazon GuardDuty
Amazon GuardDuty - A threat detection service that continuously monitors your AWS accounts and workloads for malicious activity and delivers detailed security findings for visibility and remediation. [(Link to mindmap version 1.9)](https://www.xmind.net/m/D6vnHm)


## Amazon Inspector
Amazon Inspector - An automated vulnerability management service that continually scans AWS workloads for software vulnerabilities and unintended network exposure.

The original Inspector (prior to re:Invent) is now called Inspector Classic. The new Amazon Inspector, a completely rearchitected and redesigned version of Amazon Inspector Classic, is now available across AWS Regions. The new Amazon Inspector has expanded coverage to add support for container images residing in Amazon Elastic Container Registry (Amazon ECR) in addition to EC2 instances. The new Amazon Inspector offers multi-account support through integration with AWS Organizations, and continual software vulnerability and network reachability scanning based on common vulnerabilities and exposures (CVEs). We encourage you to explore and use these and other new and improved features, and to benefit from the significantly enhanced security value. [(Link to mindmap version 1.12)](https://www.xmind.net/m/22EXUr)


## AWS CloudTrail (and intro to CloudTrail Lake)
AWS CloudTrail is an AWS service that helps you enable governance, compliance, and operational and risk auditing of your AWS account. Actions taken by a user, role, or an AWS service are recorded as events in CloudTrail. Events include actions taken in the AWS Management Console, AWS Command Line Interface, and AWS SDKs and APIs.

This mindmap also includes the recently released CloudTrail Lake.  Cloud Trail Lake is a managed data lake that lets organizations aggregate, immutably store, and query events recorded by CloudTrail for auditing, security investigation, and operational troubleshooting. This new platform simplifies CloudTrail analysis workflows by integrating collection, storage, preparation, and optimization for analysis and query in the same product. This removes the need to maintain separate data processing pipelines that span across teams and products to analyze CloudTrail events.  [(Link to mindmap version 1.10)](https://www.xmind.net/m/sY4HG3)


## AWS Config
AWS Config is a service that enables you to assess, audit, and evaluate the configurations of your AWS resources. Config continuously monitors and records your AWS resource configurations and allows you to automate the evaluation of recorded configurations against desired configurations. With Config, you can review changes in configurations and relationships between AWS resources, dive into detailed resource configuration histories, and determine your overall compliance against the configurations specified in your internal guidelines. This enables you to simplify compliance auditing, security analysis, change management, and operational troubleshooting. [(Link to mindmap version 1.6)](https://www.xmind.net/m/ACQQq3)


## Amazon Detective
AWS security services like Amazon GuardDuty, Amazon Macie, and AWS Security Hub as well as partner security products can be used to identify potential security issues, or findings. These services are really helpful in alerting you when something is wrong and pointing out where to go to fix it. But sometimes there might be a security finding where you need to dig a lot deeper and analyze more information to isolate the root cause and take action. Determining the root cause of security findings can be a complex process that often involves collecting and combining logs from many separate data sources, using extract, transform, and load (ETL) tools or custom scripting to organize the data, and then security analysts having to analyze the data and conduct lengthy investigations.

Amazon Detective simplifies this process by enabling your security teams to easily investigate and quickly get to the root cause of a finding. Amazon Detective can analyze trillions of events from multiple data sources such as Virtual Private Cloud (VPC) Flow Logs, AWS CloudTrail, and Amazon GuardDuty, and automatically creates a unified, interactive view of your resources, users, and the interactions between them over time. With this unified view, you can visualize all the details and context in one place to identify the underlying reasons for the findings, drill down into relevant historical activities, and quickly determine the root cause.  [(Link to mindmap version 1.13)](https://www.xmind.net/m/rdJPsS)


## Amazon Macie
Amazon Macie is a fully managed data security and data privacy service that uses machine learning and pattern matching to help you discover, monitor, and protect sensitive data in your AWS environment.

Macie automates the discovery of sensitive data, such as personally identifiable information (PII) and financial data, to provide you with a better understanding of the data that your organization stores in Amazon Simple Storage Service (Amazon S3). Macie also provides you with an inventory of your S3 buckets, and it automatically evaluates and monitors those buckets for security and access control. Within minutes, Macie can identify and report overly permissive or unencrypted buckets for your organization.

If Macie detects sensitive data or potential issues with the security or privacy of your data, it creates detailed findings for you to review and remediate as necessary. You can review and analyze these findings directly in Macie, or monitor and process them by using other services, applications, and systems. [(Link to mindmap version 1.06)](https://www.xmind.net/m/BDQYjp)


## AWS Audit Manager
AWS Audit Manager helps you continuously audit your AWS usage to simplify how you assess risk and compliance with regulations and industry standards. Audit Manager automates evidence collection to reduce the “all hands on deck” manual effort that often happens for audits and enable you to scale your audit capability in the cloud as your business grows. With Audit Manager, it is easy to assess if your policies, procedures, and activities – also known as controls – are operating effectively. When it is time for an audit, AWS Audit Manager helps you manage stakeholder reviews of your controls and enables you to build audit-ready reports with much less manual effort.

AWS Audit Manager’s prebuilt frameworks help translate evidence from cloud services into auditor-friendly reports by mapping your AWS resources to the requirements in industry standards or regulations, such as CIS AWS Foundations Benchmark, the General Data Protection Regulation (GDPR), and the Payment Card Industry Data Security Standard (PCI DSS). You can also fully customize a framework and its controls for your unique business requirements. Based on the framework you select, Audit Manager launches an assessment that continuously collects and organizes relevant evidence from your AWS accounts and resources, such as resource configuration snapshots, user activity, and compliance check results. [(Link to mindmap version 1.06)](https://www.xmind.net/m/AY2Rgu)


## AWS Managed Services (AMS)
AWS Managed Services (AMS) helps you operate your AWS infrastructure more efficiently and securely. Leveraging AWS services and a growing library of automations, configurations, and run books, AMS can augment and optimize your operational capabilities in both new and existing AWS environments. Whether customers are just getting started, migrating a data center, or building optimized solutions in the cloud, ongoing operational excellence is a critical component to success in the cloud. AMS can help augment your cloud operations skills and experience as a short term accelerator or long term solution; letting you focus on transforming your applications and business in the cloud. AMS provides you operational flexibility, enhances security and compliance, and will help you optimize capacity and take action on identified cost savings. AMS provides a consistent operating model for your entire AWS fleet leveraging detective guardrails, monitoring, security, and incident management best practices for both traditional and modernized workloads.  [(Link to mindmap version 1.03)](https://www.xmind.net/m/7zGWSf)


## AWS Security
This security mindmap is a high-level representation of the various ways AWS can help customers with security, compliance, and governance, by showcasing not only AWS native (Security Domains) and partner solutions, but also ways in which AWS and/or our security partners can help deploy and manage these solutions.  Finally, I am including a branch in the mindmap on Learning & Guidance with links to many of the training and reference materials on the best practices for deploying solutions in the AWS cloud. [(Link to mindmap version 1.11)](https://www.xmind.net/m/f35UhU)

