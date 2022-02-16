---
title: Architecture | mmesh
description: mmesh cloud integration platform
topic: mmesh
chapter:
  id: concepts
  label: Concepts
page:
  name: architecture
  label: Architecture
position: 202
---

## Design Principles

mmesh is an all-in-one, hybrid cloud integration platform designed to be **simple**, **scalable**, **secure** and **easy-to-use**.

You won't need to be an expert network or systems engineer to take full advantage of mmesh.

mmesh can be an excellent choice for everyone who is moving to the cloud and looks for an easy-to-use but feature-rich, multi-cloud integration platform to reduce complexity and costs.

mmesh allows you to simplify your infrastructure deployments and get rid of complex network integrations.

## Abstraction Model

The mmesh architecture is based on a hierarchical model composed by four types of logical entities: `tenants`, `networks`, `subnets` and `nodes`.

With these components you design your own [mmesh topology](/docs/mmesh/networking/topology): an unified abstraction overlay built on top of your cloud and traditional environments.

#### [Tenant](/docs/mmesh/networking/topology#tenant)

A [tenant](/docs/mmesh/networking/topology#tenant) is a logical component of mmesh that groups networks.

#### [Network](/docs/mmesh/networking/topology#network)

A [network](/docs/mmesh/networking/topology#network) is a logical component of mmesh that groups subnets.

#### [Subnet](/docs/mmesh/networking/topology#subnet)

A [subnet](/docs/mmesh/networking/topology#subnet) is a logical component of mmesh that groups nodes.

#### [Node](/docs/mmesh/networking/nodes)

A [node](/docs/mmesh/networking/nodes) is any system connected to a mmesh subnet.
