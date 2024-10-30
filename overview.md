---

copyright:
  years: 2024, 2024
lastupdated: "2024-10-30"


keywords: containers
subcollection: containers-hub

---


{{site.data.keyword.attribute-definition-list}}

# Understanding Containers in {{site.data.keyword.cloud_notm}}
{: #overview}

Learn what containers are and how you can use them in your app development processes on {{site.data.keyword.cloud_notm}}.
{: shortdesc}

{{../containers/overview.md#what-are-containers-overview}}


## Why might I use containers?
{: #overview-why}

Most people want to do one of the following tasks by using containers.

I want to run an HTTP app.
:   I've got some code that I want to deploy for my users to access.

I want to run batch jobs.
:   I've got repeatable tasks I want to run on a regular basis for testing or other purposes.

I want to enforce tight security requirements and have network control over a system of containers.
:   I've got more complex workloads that I want to automate, isolate, secure, manage, and monitor. 

## What products are available to me?
{: #product-list}

With these container product options, you can also choose to store images in {{site.data.keyword.registrylong}}.

|Product|Tenancy|Cost|Management|Skills
|-----|-----|-----|-----|-----|
|{{site.data.keyword.codeenginefull}}|Multi-tenant (Shared)|Pay when the workloads run|Manage your app in a container|No infrastructure skills required|
|{{site.data.keyword.containerfull}}|Single-tenant (Dedicated)|Billing by cluster|Manage a cluster of containers|Infrastructure and networking skills required|
|{{site.data.keyword.openshiftlong}}|Single-tenant (Dedicated)|Billing by cluster|Manage a cluster of containers|Infrastructure and networking skills required|
{: summary="The rows are read from left to right. The resource area of comparing responsibilities is in the first column, with the responsibilities of IBM in the second column and your responsibilities in the third column."}
{: caption="Containers product comparison" caption-side="bottom"}

[Learn more about the differences between these products.](/docs/containers-hub?topic=containers-hub-comparison)
