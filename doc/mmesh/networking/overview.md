---
title: Networking | mmesh
description: mmesh hybrid cloud integration platform
topic: mmesh
chapter:
  id: networking
  label: Networking
page:
  name: overview
  label: Overview
position: 300
---

This documentation section helps you learn about the networking concepts and features of mmesh.

You don't need to be an network expert to take full advantage of mmesh, although the platform also supports some advanced features designed to meet service provider requirements in scenarios with complex network environments.

Browse the topics below to learn more.

## Network Abstraction

mmesh acts as a compatibility layer on top of your cloud and traditional environments, allowing you to create a seamless [virtual topology](/docs/mmesh/networking/topology) where you can define your [security policies](/docs/mmesh/networking/network-security#security-policies) and access controls ([RBAC](/docs/mmesh/iam/authorization)) to operate and [automate](/docs/mmesh/automation/overview) your [nodes](/docs/mmesh/networking/nodes) in a simpler and unified way.

#### [Topology](/docs/mmesh/networking/topology)

Learn how to build your mmesh [topology](/docs/mmesh/networking/topology).

#### [Nodes](/docs/mmesh/networking/nodes)

A `node` is any system connected to your mmesh topology.

Find more information and learn how to manage them in the [Nodes](/docs/mmesh/networking/nodes) section.

## Network Security

One of the main goals of mmesh is to help you enhance your infrastructure security in hybrid cloud environments. Easily, without requiring complex tools often difficult to configure, or expensive deployments of legacy equipment.

#### [Security Policies](/docs/mmesh/networking/network-security#security-policies)

[Security policies](/docs/mmesh/networking/network-security#security-policies) act as distributed firewalls and protect the [nodes](/docs/mmesh/networking/nodes) connected to mmesh.

#### [End-to-End Encryption](/docs/mmesh/networking/network-security#end-to-end-encryption)

mmesh automatically enforces [end-to-end encryption](/docs/mmesh/networking/network-security#end-to-end-encryption) on all network traffic and user interactions. No configuration required.

## Service Discovery

mmesh implements a [service discovery](/docs/mmesh/network/service-discovery) system where every node connected to mmesh is published on an internal DNS subsystem with the `.mmesh.local` suffix.

You can easily integrate the `.mmesh.local` domain into your DNS infrastructure by configuring the `mmesh.local` domain as a _forward_ zone.

See [DNS Integration](/docs/mmesh/networking/service-discovery#dns-integration) for more details.

## Advanced Features

mmesh supports [advanced features](/docs/mmesh/networking/advanced-features) designed to meet service provider requirements in scenarios with complex network environments.

- [Dynamic Routing](/docs/mmesh/networking/advanced-features#dynamic-routing)
- [Address Overlapping](/docs/mmesh/networking/advanced-features#address-overlapping)
- [mmesh64](/docs/mmesh/networking/advanced-features#mmesh64)
- [High Availability](/docs/mmesh/networking/advanced-features#high-availability)

## Best Practices

Learn some tricks and recommended configurations [here](/docs/mmesh/networking/best-practices).
