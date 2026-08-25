---

copyright:
  years: 2024, 2026

lastupdated: "2026-08-25"

keywords: containers, IBM Cloud, International Business Machines (IBM), app development, containerization

subcollection: containers-hub

---


{{site.data.keyword.attribute-definition-list}}

# Developing apps with containers on {{site.data.keyword.cloud_notm}}
{: #overview}

Learn to use containers for app development on {{site.data.keyword.cloud_notm}}, including product options and use cases.
{: shortdesc}

{{../containers/overview.md#what-are-containers-overview}}


## Why use containers?
{: #overview-why}

Containers represent the industry standard for modern, scalable application development. Use containers to achieve the following key objectives.

You want to run a Hypertext Transfer Protocol (HTTP) app.
:   Containerized deployment guarantees high availability, isolated runtime environments, and reliable, consistent access to your applications over HTTP.

You want to run batch jobs.
:   Containers ensure isolated, repeatable, and scheduled execution of automated testing and high-throughput data processing tasks.

You want to enforce tight security requirements and have network control over a system of containers.
:   Containerized environments provide robust security isolation, fine-grained network control, and comprehensive workload monitoring to satisfy strict enterprise policies.


## What products are available to me?
{: #product-list}

With these container product options, you can also choose to store images in {{site.data.keyword.registrylong}}.

| Product | Tenancy | Cost | Management | Skills |
| ------- | ------- | ---- | ---------- | ------ |
| {{site.data.keyword.codeenginefull}} | Multi-tenant (Shared) | Pay when the workloads run | Manage your app in a container | No infrastructure skills required |
| {{site.data.keyword.containerfull}} | Single-tenant (Dedicated) | Billing by cluster | Manage a cluster of containers | Infrastructure and networking skills required |
| {{site.data.keyword.openshiftlong}} | Single-tenant (Dedicated) | Billing by cluster | Manage a cluster of containers | Infrastructure and networking skills required |
{: caption="Containers product comparison" caption-side="bottom"}

[Learn more about the differences between these products.](/docs/containers-hub?topic=containers-hub-comparison)
