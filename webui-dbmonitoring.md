---

copyright:
  years: 2018, 2019
lastupdated: "2019-03-26"

keywords: database monitoring, database cluster, database metrics

subcollection: hyper-protect-dbaas

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}


# Database monitoring

After you have enabled database monitoring, you can view the database metrics using Grafana.

## Before you begin
{: #database_monitoring_byb}

<ol>
<li>Be sure to have access to at least one Cloud Foundry organization and space. The organization and space must be in the location of your database cluster, except database clusters residing in Washington (us-east), which need access to an organization and space in Dallas (us-south) for monitoring.

<p>For information about how to obtain such access, see https://cloud.ibm.com/docs/iam?topic=iam-mngcf#mngcf.</p>
</li>

<li>Make sure that all instances of the database cluster are running.
</li>

<li>In the {{site.data.keyword.cloud}} {{site.data.keyword.ihsdbaas_full}} dashboard, select the Monitoring tab.
</li>
</ol>

## Enabling database monitoring

In case the message "Monitoring is disabled" is displayed in the Monitoring tab:

1. Click **Enable**.
2. In the Enable Monitoring window, select your organization and space, then click **Submit**.


## Viewing database metrics

There are two ways to view the metrics in Grafana:

- Copy the displayed link, then open a new tab or window and paste the link to the browser.
- Click **View in Grafana**.

To display the metrics in a new dashboard in Grafana, select the upper left icon, then select **Dashboards > New**.

For more information about using Grafana, see https://cloud.ibm.com/docs/services/cloud-monitoring?topic=cloud-monitoring-getting-started-with-ibm-cloud-monitoring#getting-started-with-ibm-cloud-monitoring.
