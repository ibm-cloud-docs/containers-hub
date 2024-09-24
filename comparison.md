---

copyright:
  years: 2024, 2024
lastupdated: "2024-09-24"


keywords: containers
subcollection: containers-hub

---


{{site.data.keyword.attribute-definition-list}}

# Comparing {{site.data.keyword.cloud_notm}} Containers products
{: #comparison}

{{site.data.keyword.cloud_notm}} offers several products for deploying containers.
{: shortdesc}

## What products are available to me?
{: #comparison-tools}

|Product|Tenancy|Cost|Management|Skills
|-----|-----|-----|-----|-----|
|{{site.data.keyword.codeenginefull}}|Multi-tenant (Shared)|Pay when the workloads run|Manage your app in a container|No infrastructure skills required|
|{{site.data.keyword.containerfull}}|Single-tenant (Dedicated)|Billing by cluster|Manage a cluster of containers|Infrastructure and networking skills required|
|{{site.data.keyword.openshiftlong}}|Single-tenant (Dedicated)|Billing by cluster|Manage a cluster of containers|Infrastructure and networking skills required|
{: summary="The rows are read from left to right. The resource area of comparing responsibilities is in the first column, with the responsibilities of IBM in the second column and your responsibilities in the third column."}
{: caption="Table 1. Containers product comparison" caption-side="bottom"}

### Storing images
{: #comparison-reg}

With all of these container product options, you can also choose to store images in {{site.data.keyword.registrylong}}.

{{../Registry/registry_overview.md#table_registry_overview_benefits}}


## How do I choose?
{: #comparison-choose}

Learn a little bit about each product to know which one suits your needs best.


### {{site.data.keyword.codeenginefull_notm}}
{: #comparison-ce}

{{../codeengine/about.md#about-par}}

{{../codeengine/about.md#benefits-table}}

[Get started with {{site.data.keyword.codeenginefull_notm}}](/docs/codeengine?topic=codeengine-getting-started).


### {{site.data.keyword.containerlong_notm}}
{: #comparison-iks}

{{../containers/overview.md#overview-iks}}

{{../containers/_include-segments/service-benefits.md}}

[Get started with {{site.data.keyword.containerlong_notm}}](/docs/containers?topic=containers-getting-started).


### {{site.data.keyword.openshiftlong_notm}}
{: #comparison-os}

{{../openshift/overview.md#what-is-openshift-overview-par}}

{{../openshift/_include-segments/service-benefits.md}}

[Get started with {{site.data.keyword.containerlong_notm}}](/docs/openshift?topic=containopenshifters-getting-started).


### How do I choose between {{site.data.keyword.containerlong_notm}} and {{site.data.keyword.openshiftlong_notm}}?
{: #comparison-iks-os}

If you know you want to manage your containers in a cluster, consider these differences as you choose between these two products.

{{../containers/overview.md#iks-os-table}}
