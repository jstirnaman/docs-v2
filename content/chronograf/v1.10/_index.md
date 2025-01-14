---
title: Chronograf 1.10 documentation
description: >
  Chronograf is InfluxData's open source web application.
  Use Chronograf with the other components of the TICK stack to visualize your
  monitoring data and easily create alerting and automation rules.
menu:
  chronograf_1_10:
    name: Chronograf v1.10
weight: 1
---

Chronograf is InfluxData's open source web application.
Use Chronograf with the other components of the [TICK stack](https://www.influxdata.com/products/) to visualize your monitoring data and easily create alerting and automation rules.

## Key features

### Infrastructure monitoring

* View all hosts and their statuses in your infrastructure
* View the configured applications on each host
* Monitor your applications with Chronograf's [pre-created dashboards](/chronograf/v1.10/guides/using-precreated-dashboards/)

### Alert management

Chronograf offers a UI for [Kapacitor](https://github.com/influxdata/kapacitor), InfluxData's data processing framework for creating alerts, running ETL jobs, and detecting anomalies in your data.

* Generate threshold, relative, and deadman alerts on your data
* Easily enable and disable existing alert rules
* View all active alerts on an alert dashboard
* Send alerts to the supported event handlers, including Slack, PagerDuty, HipChat, and [more](/chronograf/v1.10/guides/configuring-alert-endpoints/)

### Data visualization

* Monitor your application data with Chronograf's [pre-created dashboards](/chronograf/v1.10/guides/using-precreated-dashboards/)
* Create your own customized dashboards complete with various graph types and [template variables](/chronograf/v1.10/guides/dashboard-template-variables/)
* Investigate your data with Chronograf's data explorer and query templates

### Database management

* Create and delete databases and retention policies
* View currently-running queries and stop inefficient queries from overloading your system
* Create, delete, and assign permissions to users (Chronograf supports [InfluxDB OSS](/{{< latest "influxdb" "v1" >}}/administration/authentication_and_authorization/#authorization) and InfluxDB Enterprise user management)


### Query management

* View a list of databases, queries and their status
* Kill a query
* Download a list of queries in your instance to a CSV file 

### Multi-organization and multi-user support

{{% note %}}
**Note:** To use this feature, OAuth 2.0 authentication must be configured.
Once configured, the Chronograf Admin tab on the Admin menu is visible.
For details, see [Managing Chronograf security](/chronograf/v1.10/administration/managing-security/).
{{% /note %}}

* Create organizations and assign users to those organizations
* Restrict access to administrative functions
* Allow users to set up and maintain unique dashboards for their organizations
