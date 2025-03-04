---
title: Energy consumption data tutorial
excerpt: Learn how to query energy consumption data
products: [cloud]
keywords: [tutorials, energy, learn]
tags: [tutorials, beginner]
layout_components: [next_prev_large]
content_group: Analyze energy consumption data
---

# Analyze energy consumption data

When you are planning to switch to a rooftop solar system it isn't easy, even
with a specialist at hand. You need details of your power consumption, typical
usage hours, or distribution over a year. Collecting consumption data at the
granularity of a few seconds is key to finding all the answers for more
precision. This tutorial uses energy consumption data from a typical household
for over a year. Because nearly all of this data is time-series data, proper
analysis requires a purpose-built time-series database, like Timescale.

In this tutorial you can construct queries that look at how many watts were
consumed, and when. Additionally, you can visualize the energy consumption data
in Grafana.

## Prerequisites

Before you begin, make sure you have:

*   Signed up for a [free Timescale account][cloud-install].
*   [](#)<Optional /> [Signed up for a Grafana account][grafana-setup] to graph queries.

## Steps in this tutorial

This tutorial covers:

1.  [Setting up your dataset][dataset-energy]: Set up and connect to a
    Timescale service, and load data into the database using `psql`.
1.  [Querying your dataset][query-energy]: Analyze a dataset containing energy
    consumption data using Timescale and PostgreSQL, and visualize the
    results in Grafana.

## About querying data with Timescale

This tutorial uses sample energy consumption data to show you how to construct
queries for time-series data. The analysis you do in this tutorial is
similar to the kind of analysis households might use to do things like plan
their solar installation, or optimize their energy use over time.

It starts by teaching you how to set up and connect to a Timescale database,
create tables, and load data into the tables using `psql`.

You then learn how to conduct analysis and monitoring on your dataset. It also walks
you through the steps to visualize the results in Grafana.

[dataset-energy]: /tutorials/:currentVersion:/energy-data/dataset-energy/
[query-energy]: /tutorials/:currentVersion:/energy-data/query-energy/
[cloud-install]: /getting-started/:currentVersion:/#create-your-timescale-account
[grafana-setup]: /use-timescale/:currentVersion:/integrations/observability-alerting/grafana/installation/
